教程

- 基础
  - https://www.bilibili.com/video/BV1uW4y1v7xr
    - 全部都可以看这个大佬的：[水木珞研电气考研](https://space.bilibili.com/397697344)

  - 嵌入式大全：https://www.bilibili.com/video/BV1FA411v7YW

- [硬件工程师如何找到类似于GitHub这样的社区？](https://www.zhihu.com/question/26053396/answer/3009987847)
- 项目大全

  - esp32+51：https://www.bilibili.com/video/BV1k44y137EV
  - 基础：https://www.bilibili.com/video/BV1EB4y1N7iD
- 学习路线
  - https://www.bilibili.com/video/BV14V4y1t7Kn
  - https://juejin.cn/post/7310112724945141760
- 电子书
  - [imKeYan/EmbedBooks](https://github.com/imKeYan/EmbedBooks?tab=readme-ov-file#05---操作系统)

- [2021年50家国产MCU厂商](https://zhuanlan.zhihu.com/p/435216264)
- 学习物联网的网站

  - B站：大多数大佬都在这里
  - https://blog.csdn.net/weixin_51218153/article/details/122938146
  - [zhengnianli/EmbedSummary: 精品嵌入式资源汇总 (github.com)](https://github.com/zhengnianli/EmbedSummary)
  - micro-python：[王铭东](https://space.bilibili.com/457643342)
  - [会选科技](https://space.bilibili.com/230131041)
  - [小蜜蜂老师](https://space.bilibili.com/397050828)
  - [奇遇单片机](https://space.bilibili.com/1508566862)
  - [洋桃电子](https://space.bilibili.com/277276709?spm_id_from=333.337.search-card.all.click)
  - [乐鑫信息科技](https://space.bilibili.com/538078399?spm_id_from=333.999.0.0)
  - [嘉立创](https://space.bilibili.com/1020770905?spm_id_from=333.999.0.0)
  - [普中开源电子分享网 - Powered by Discuz! (prechin.net)](http://www.prechin.net/)
  - 产品拆解
    - https://www.52audio.com/archives/category/teardowns
  - [硬核拆解投稿视频-硬核拆解视频分享-哔哩哔哩视频 (bilibili.com)](https://space.bilibili.com/427494870/video)
  - 方案：https://www.iotku.com/
  - 标准：http://www.gov.cn/fuwu/bzxxcx/bzh.htm
  - 专利申请：https://www.patenthub.cn/
  - 选型：https://www.hqchip.com/app/1378
  - 外设：https://www.panelook.cn/index_cn.php
  - 手册：https://www.21icsearch.com/
  - 展会：https://www.chinapp.com/zhanhui
  - 开源：https://gitee.com/explore
    - [EmbedSummary: 嵌入式大杂烩资源汇总 (gitee.com)](https://gitee.com/zhengnianli/EmbedSummary?_from=gitee_search#37-调试器)
- 工具网站
  - 图片
    - https://wallhaven.cc/search
    - [极简壁纸 (bizhi1.com)](https://bizhi1.com/item-cat/ai-generated)




## 核心关注点

- 电路的基础知识
  - 
- 能看懂、并设计电路原理图
- 现场安装、设备调试

  - 调试分软件和硬件调试
  - 设备调试：万用表、烙铁、示波器、频谱仪
- c、c++
- 51
- arduino
- 核心：stm32/esp32
- 通信协议

  - usb、spi、i2c、uart、mqtt
- linux系统
- QT开发：嵌入式linux开发
- RTOS

  - FreeRTOS
- plc编程（可选）
- 绘图软件：CAD、EPLAN
- 物联网应用：连接到阿里云
- 学会测试
  - 设计测试用例（列举各种场景）





每一种型号的芯片都需要重新学习吗？

- 同一系列的芯片只需要学一种，比如STM32F1系列
- 同一内核的芯片只需要学一种
- 同一个公司的芯片只用方法都很相似的



有哪些参考资料？



如何获得这些参考资料？



技术方案哪里看？怎么看？



参考手册RM（也叫用户手册）、数据手册DS有啥区别？

- 参考手册：比较全面，告诉用户如何使用
- 数据手册：侧重于硬件的介绍



开发流程

- 编码：需要代码编辑器，如keil5，它是集成开发工具，有编辑，编译，调试功能
- 编译：需要编译器，将代码转换成二进制
- 调试：需要调试软件和调试器（如ST-LINK）



怎么找厂商？

- 浏览器搜索
  - 根据类型找：比如串口屏厂商排名
- 淘宝找，看下销量



怎么判断是开发板或者是芯片出问题了？

- 

## 求助

投石问路：找知道的人，找行业内的人去跑一下，这样

可以去





## 近期问题

电路原理图都看不懂啊

时序图不会看

他们说的很多概念你不清楚

- 比如继电器

需要补一下电路的基础，数电、模电基础，找电子书或者是视频

- 每天补半小时

怎样方便的给我们的芯片输入一些信号，来实现调试？

- 是通过GPIO吗？



## 测试方法

要找一下视频，看下别人是怎么调试，排错的？

代码没报错，一般都是没有问题的

可以测一下引脚的电压

- 比如代码写了，但继电器没反应



## 定位问题技巧

接线错误

- 没有接地
- 正负极接反了

看错文档了

代码没写入

代码逻辑有问题

设备损坏了

- 



## 测试

芯片最好能有输入，比如遥控器

- 不然我没法测试啊



## 通信

关注点

- 通信协议
  - 大致分为有线、无线
- 传输速度
- 传输距离
- 电源、功耗
- 同步/异步通信
- 安全性
- 硬件配置
- 基于应用的需求
  - 实时性
  - 可靠性



无线通信有哪些？

- 蓝牙
- wifi
- 2.4G/3/4/5g
- 红外
- NFC
- Zigbee
- LoRa

有线通信有哪些？



## 蓝牙

分类

- 经典
- BLE



蓝牙网关

：用于做中转站，可以将蓝牙网络与其他类型的网络连接，比如



蓝牙主机

：是蓝牙网络中的主动设备，能够发起连接，控制连接，协调通信



## WiFi

：是WLAN的一种最常见的实现方式





## 问题



stm32与esp32适用场景

- stm32适用范围比较广，偏向于工业
- esp32偏向于家居

嵌入式分类

- 嵌入式底层
- 嵌入式应用，我选择的



电路图怎么看？

- 

mcu就是单片机的英文，别名微控制器

- microcontroller unit

mpu是微处理器

- microprocessors unit

mcu与mpu区别

- mcu有更多的集成外设

51、stm32、plc区别

- 共同点：都是单片机
- 不同点：plc没那么灵活，但是集成度比较高

plc？可编程的逻辑控制器

pcb？

外设与接口有啥区别？

- 外设本身一种设备，外设是相对cpu来说的，外设通过不同的接口与cpu通信，外设可以用来扩展系统功能的
  - io：键盘、显示（LED、LCD)、硬盘、
  - 通信有关的：蓝牙、wifi、以太网
- 接口则是一种标准，设备与处理器之间的通信标准

触摸屏跟显示屏有啥区别？

- 显示屏一般不支持用户触摸输入，而触摸屏可以

数字信号与模拟信号区别？

- 

编程方式

- 寄存器方式
- 库函数方式

时序图应该怎么看？

DAP有啥用？Debug Access Port

- 可以方便调式，有些DAP是被内嵌到开发板上的

通信协议与通信技术区别

- 没啥太大区别

WLAN与wifi区别

- 前者包括后者，后者是前者某一环节的其中一种技术

外设会引申处引脚，比如GPIO的PA0,PA1之类的引脚

- 

引脚悬空会导致电平不确定

- 

配网

：设备连接到网络（不一定是互联网）的动作

分类

- wifi配网
- 蓝牙配网
- 有线配网

配网步骤

- 获取网络信息
- 身份认证
- 联立网络连接

配网的场景

- 新设备接入
- 网络更改
  - 修改网络名称或者是密码
  - 重置为出厂设置

不管是蓝牙还是wifi

- 有效范围都是在20米到100米

以太网与wifi区别

- 以太网有线，wifi是无线

屏幕

- 显示屏：只能显示，无法触摸操作
- 电阻屏：压力传感，稳定性好
- 电容屏：灵敏度高

怎么快速的去查看单片机的输出？

- 

电路板为啥需要接GND？

- 为了构成闭合回路，不然会有很多意外

开发时候买到的一般都是开发板，而不是只买到芯片

- 只买芯片，你啥也干不了，没法调试的

