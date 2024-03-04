esp32是国产芯片，集成度比较高，学习难度也比较低

教程

- 官网：[ESP-IDF 物联网开发框架｜乐鑫科技 (espressif.com)](https://www.espressif.com/zh-hans/products/sdks/esp-idf)
- esp32-idf入门
  - [ESP-IDF 入门指南 | 乐鑫科技 (espressif.com)](https://idf.espressif.com/zh-cn/index.html)
  - https://www.bilibili.com/video/BV1tY4y1L7HV
  - https://www.bilibili.com/video/BV1ah4y177mR
- [入门](https://www.bilibili.com/video/BV1ah4y177mR?p=4&vd_source=522153461914a766fc002cc8619314e4)
- 极客侠：https://docs.geeksman.com/esp32/MicroPython
- 



## 核心关注点

学习芯片有哪些资料可以翻？

- 官方文档
- esp-idf：内置了很多demo
  - 它的demo怎么看懂啊？

- 引脚清单
- 原理图

学习它的开发流程

- 我希望很多东西应该是配置生成的，而不是手敲的





如果用esp32的idf如何开发？

- 



## 搭建开发环境





## WLAN

wifi是wlan的一种实现方式，wlan还有很多种实现方式，lora





## 坑

esp32 idf不能用git bash，只能用powshell

- 不然命令会执行失败，因为少了很多反斜杠



## 问题

esp32常用哪个语言进行开发？

- c、c++
- python
- lua



esp32相比stm32有啥优点？

- 集成度：内置了蓝牙、wifi
- 功耗：功耗较低
- 外设：
- 价格
- 易用性
- 闪存容量

esp32的使用场景

- 

reset和boot按键区别？

- reset用于重启硬件：按一下即可
- boot则是用于设置引导模式，一般有2种模式，需要长按3秒
  - 串口下载模式
  - OTA模式：通过wifi来升级

三种型号

- S：性能最好，10元+
- C：性能适中，最便宜
- H：专注于蓝牙，10元左右

esp-idf

- iot development framework：物联网开发框架

什么时候需要用到云编译，什么时候可以直接下载固件？

- 云编译
- 
