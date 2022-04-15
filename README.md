# Endermite
Endermite是一个致力于实现高性能独立Minecraft服务器的项目
 
具有以下特点：
- 使用C++23编写，提供最接近极限的性能
- 完全的多线程，最大化利用CPU资源
- 完全手动管理内存，最大化利用内存资源
- 改进世界储存格式，提高硬盘的利用效率
- 忠于vanilla，各种特性尽可能贴近Java版
- 提供众多可选的原版不具有的功能，如无限制建造高度
- 同时支持Java版和基岩版协议，自带互通服
- 主要跟进高版本开发，将尽可能跟进官方最新进度
- 开源免费，任何人都可以参与
- 提供诸多可修改参数，便于自定义服务器
- 完全的跨平台，同时提供Windows/Linux/OS X多个系统的多个指令集的可执行文件，但优先保证Linux的性能
- 提供定时备份及备份管理功能
- 可调节的区块强加载功能

未来可能会实现的功能：
- 实现一个java bridge，将翻译部分spigot/paper API以兼容插件生态
- 兼容官方数据包，行为包
- 提供负载均衡以支持超大型服务器
- 支持使用openCL调用GPU加速部分并行计算
- 提供一个使用PHP编写的可视化管理面板
- 提供官方Docker分发
- 实现官方命令
- QQ/Discord机器人
- 网页卫星地图
- 提供一个完善API以支持使用Javascript编写的扩展和第三方插件
- 实现replay功能
- 内建的创世神