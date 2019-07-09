# 操作系统原理实验

*   中山大学（SYSU）
*   数据科学与计算机学院（SDCS）
*   操作系统原理实验（Operating Systems Laboratory, DCS209）
*   课程教师：凌应标
*   2019 春季学期（Spring 2019）

作者：[Jed](https://www.jeddd.com/)



## 实验目录

| 序号 | 名称                                                   | 简介                                                   | 镜像文件                                                     | 成绩 |
| ---- | ------------------------------------------------------ | ------------------------------------------------------ | ------------------------------------------------------------ | ---- |
| 1    | [接管裸机的控制权](项目1_接管裸机的控制权)             | 在裸机（虚拟机）上运行自己的程序                       | [jed_stone.img](项目1_接管裸机的控制权/jed_stone.img?raw=true) | A++  |
| 2    | [加载用户程序的监控程序](项目2_加载用户程序的监控程序) | 实现监控程序（原始操作系统）执行用户程序这一项基本功能 | [JedOS_v1.0.img](项目2_加载用户程序的监控程序/JedOS_v1.0.img?raw=true) | A++  |
| 3    | [开发独立内核的操作系统](项目3_开发独立内核的操作系统) | 用C和汇编实现操作系统内核，并增加批处理能力            | [JedOS_v1.1.img](项目3_开发独立内核的操作系统/JedOS_v1.1.img?raw=true) | A+++ |
| 4    | [异步事件编程技术](项目4_异步事件编程技术)             | 用时钟中断、键盘中断等处理异步事件                     | [JedOS_v1.2.img](项目4_异步事件编程技术/JedOS_v1.2.img?raw=true) | A+++ |
| 5    | [实现系统调用](项目5_实现系统调用)                     | 实现原型操作系统中一些基本的系统调用                   | [JedOS_v1.3.img](项目5_实现系统调用/JedOS_v1.3.img?raw=true) | A++  |
| 6    | [二状态进程模型](项目6_二状态进程模型)                 | 多进程分时系统，采用时间片轮转调度进程运行             | [JedOS_v1.4.img](项目6_二状态进程模型/JedOS_v1.4.img?raw=true) | A+++ |
| 7    | [进程控制与通信](项目7_进程控制与通信)                 | 五状态进程模型，支持 fork、wait 和 exit                | [JedOS_v1.5.img](项目7_进程控制与通信/JedOS_v1.5.img?raw=true) | A+++ |



## 说明

* GCC + NASM 实模式（16 位兼容的 32 位代码）；
* Bash 脚本自动编译、链接、整合（非 Makefile）；
* 功能朴素，无花里胡哨或高端效果；
* 代码质量一般，未作工程化考量；
* 仅在 VMware Workstation Pro 15 中测试软盘镜像；
* 报告文档详细；
* 成绩—时间性价比较高；
* 仅完成至实验 7。



## License

MIT