教程：

- [LuatOS 文档](https://wiki.luatos.com/luaGuide/introduction.html)
- [每日喝粥的个人空间-每日喝粥个人主页-哔哩哔哩视频 (bilibili.com)](https://space.bilibili.com/532832)
- [技术服务论坛 (openluat.com)](https://chat.openluat.com/)



## 核心关注点

学习路线

- lua语法
- task框架
- 开发环境搭建
- 代码烧录
- 仓库demo
- 



## number

```lua
local str="123"
local num=tonumber(str)
```





## string

tostring(0x41)，为啥会自动转成10进制数





## http

静态ip配置无效

为啥它的发送要配上一些额外的参数？

- http.request("GET", _G.SEND_URL, nil, nil, { adapter = socket.LWIP_AP }).wait()



## wlan

如何看连接了哪些设备？

为啥一直连接失败？

scan扫描有啥用？

- 可以获取周围的wifi信息



softap是啥？

- 

AP与多个STA连接，为啥有一个走静态，剩下的动态DHCP就无法正常分配ip了

- 



## uart

传输的本质都是二进制数，或者是16进制数，

read和write接口，发送和接收都只能通过字符串的方式，而5AA506831101010000与“5AA506831101010000”不是等同的

- 发送：你要发一串16进制数，如5AA506831101010000，给串口屏，不能直接发"5AA506831101010000"，而是做一下转换，这样才是正确的发送16进制数

```lua
uart.write(string.fromHex("5AA506831101010000"))
```

- 接收：你要接收一串16进制数，uart.read只会把收到的一串16进制数转成对应的字符串，你要直观的看到16进制数，也要做一下转换

```lua
let str=uart.read(uart_pin,9)
let result1=string.toHex(str)
```



## task

如何停止死循环任务？

- 通过标志位，如isRun



## 坑

它不喜欢用花括号

- 而是用then/do和end来替代，而且只需要出现1次

没有销毁线程的方法

- 只能让他自己执行完，然后被回收





## 问题



串口中读取到的只能是字符串吗？能否是一个数组？

- 

字符串与16进制数的互转

- 

log与print有啥区别？

taskInit

- 只执行1次的任务

什么时候需要用到taskInit，什么时候需要用到多个taskInit

- 

哪些代码不需要放到taskInit中，哪些需要？

- 

为啥会出现sta死活连不上ap的情况？

- wifi配置错误
- ap配置错误
- 初始化顺序错误
  - wlan.init
  - wlan.staIp
    - 这个需要放到init之后，connect之前
  - wlan.connect
- ap负载过高
- 信道冲突，处于高密度wifi环境种
- 硬件故障



wifi连上了不代表连上了ap

- ap连接需要在wifi连接成功的基础上

有了芯片，开发板做了啥？

- 

智能配网

- 

进制转换

- 把一串16进制数转成字符串：string.fromHex("5AA5")
- 把字符串转16进制数：string



编码与字符集的关系

编码一定要先有对应的字符集吗？

一种字符集如unicode可以有多种编码方式

- 所谓编码就是生成一个地址，完成映射关系

utf8与gbk编码对应的字符集都是一样大吗？还是utf8更大

- utf8的字符集更大，gbk主要主要是针对中文的

hex编码要是借用utf8编码

- 把它的值转成16进制数

为啥读取到的内容还包括了上次的数据了

- 
