# Parallelworld
### 项目简介
---
Parallelworld 是一款运行于Android系统的沙盒产品，可以理解为android的虚拟机。可以在免root的情况下实现Xposed环境。
### 实现方案
---
在不修改APK、不修改Framework的情况下，虚拟Framework层，虚拟文件系统，模拟Android对组件的管理，虚拟应用进程等，将APK复制一份到虚拟空间中运行。

