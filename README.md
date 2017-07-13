# Xposed-脱壳工具

## 原理

Xposed框架是一款可以在不修改APK的情况下影响程序运行（修改系统）的框架服务，通过替换/system/bin/app\_process程序控制zygote进程，使得app\_process在启动过程中会加载XposedBridge.jar这个jar包，从而完成对Zygote进程及其创建的虚拟机的劫持。



