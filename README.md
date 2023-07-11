# UINIO-USB-UART

[**UINIO-USB-UART**](https://github.com/uinika/UINIO-USB-UART) 是一款分别基于[**苏州沁恒 CH343P**](https://www.wch.cn/products/CH343.html) 和[**美国芯科 CP2102**](https://www.silabs.com/interface/usb-bridges/classic/device.cp2102) 芯片的 **USB** 转 **UART** 的开源串口调试器电路设计，两款芯片都可以稳定的支持 `921600` 波特率通信。

![](./Images/PCB-3D-1.png)

![](./Images/PCB-3D-2.png)

- 板载 `RXD` 和 `TXD` 的信号读写指示灯；
- 引出了包括**串口硬件流控信号线**在内的全部片上资源；
- 采用 **16 Pin** 的 **USB Type-C** 接口，以及 PCB 拼板设计；
- 增加 **1206** 封装的自恢复保险丝，为后级电路提供短接保护；
- 预留有 `1mm` 的固定螺丝孔，便于安装至 3D 打印外壳，或者搭建成套的产品原型；
