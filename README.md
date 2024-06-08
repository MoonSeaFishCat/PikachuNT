![图片](https://github.com/MoonSeaFishCat/PikachuNT/assets/130481300/67eab13d-38d6-4a2e-a030-a51660ab63a3)

# 项目简介

Pikachu 项目是一个专门为支持 OB11 规范的协议端设计的中转信息处理项目

语言类型：易语言框架

该项目的主要目的是处理和中转协议端之间的信息

1. **信息接收**： Pikachu 可能会接收来自协议端的消息或数据，并对其进行解析和处理。

2. **数据转换**：根据 OB11 规范的要求，Pikachu 会对接收的数据进行转换或映射，以确保与协议端的兼容性。

3. **信息中转**：处理后的数据可能会被转发到其他系统、服务或组件，以实现信息的传递和共享。

4. **错误处理**：该项目可能还包括错误检测和处理机制，以确保信息的可靠传输和处理。

5. **日志记录**：为了跟踪和监控信息处理过程，Pikachu 可能会记录相关的日志信息，以便于故障排查和分析。

通过 Pikachu 项目，能够提供一个中间层来协调不同协议端之间的通信，确保信息的正确处理和传递。这样的中转处理可以提高系统的可靠性、互操作性，并简化协议端之间的集成工作。降低机器人插件的开发门槛

# 框架及SDK下载地址

[https://wwl.lanzouo.com/b00b3na0uj](https://wwl.lanzouo.com/b00b3na0uj密码:1hmz)

密码:1hmz

# 支持协议端

基于正向wss通信，只需要协议端兼容ob11，都可以使用pikachu进行信息处理

觉得好用可以帮他们点个stare

## [LLOneBot](https://github.com/LLOneBot/LLOneBot)

介绍：使你的NTQQ支持OneBot11协议进行QQ机器人开发<br />
项目地址：[https://github.com/LLOneBot/LLOneBot](https://github.com/LLOneBot/LLOneBot)<br />
备注：基本上不会冻结和屏蔽。适用于群管类或者娱乐类，不存在任何违规API，可放心使用，推荐使用这个<br />
项目文档：<br />
[https://llonebot.github.io/zh-CN/develop/api](https://llonebot.github.io/zh-CN/develop/api)<br />

一键安装地址：<br />

[https://github.com/super1207/install_llob/releases/download/0.0.3/llob_install.exe](https://github.com/super1207/install_llob/releases/download/0.0.3/llob_install.exe)


## [Lagrange.Core](https://github.com/LagrangeDev/Lagrange.Core)

介绍：NTQQ协议的一个实现，使用纯C#

项目地址：[https://github.com/LagrangeDev/Lagrange.Core](https://github.com/LagrangeDev/Lagrange.Core)

备注:支持ob11的目前最稳的PC协议端，并且有扩展API（暂时不兼容扩展API）

项目文档：

[https://lagrangedev.github.io/Lagrange.Doc/](https://lagrangedev.github.io/Lagrange.Doc/)



## [NapCatQQ](https://github.com/NapNeko/NapCatQQ)

介绍:基于NTQQ的无头Bot框架

备注：

NapCatQQ 是基于 PC NTQQ 本体实现一套无头 Bot 框架。

名字寓意 瞌睡猫QQ，像睡着了一样在后台低占用运行的无需GUI界面的NTQQ。<br />
项目地址：<br />
[https://github.com/NapNeko/NapCatQQ](https://github.com/NapNeko/NapCatQQ)<br />

项目文档：

[https://napneko.github.io/zh-CN/](https://napneko.github.io/zh-CN/)



# 具体使用教程：

1.按照对应的文档，安装并配置好对应的协议端

2.通信方式选用正向WSS

3.如下图进行配置

![图片](https://github.com/MoonSeaFishCat/PikachuNT/assets/130481300/329ff22b-aba8-45d7-ad2d-020c5874cc81)


如果 QQ在本地 框架在服务器 那么就把添加账号时的IP改成公网IP

只开正向WebSocket 其他HTTP 反向请关闭

4.配置完成

![图片](https://github.com/MoonSeaFishCat/PikachuNT/assets/130481300/ca50d1bc-c4dd-4428-a9be-46c2becb78db)


![图片](https://github.com/MoonSeaFishCat/PikachuNT/assets/130481300/7609cce6-6d8e-479f-bd6e-ee63c7fccd7d)

