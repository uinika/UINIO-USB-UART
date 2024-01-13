# UINIO-USB-UART 串口调试器

[**UINIO-USB-UART**](https://gitee.com/uinika/UINIO-USB-UART) 是一款分别基于[**苏州沁恒 CH343P**](https://www.wch.cn/products/CH343.html) 和[**美国芯科 CP2102**](https://www.silabs.com/interface/usb-bridges/classic/device.cp2102) 芯片的 **USB** 转 **UART** 的开源串口调试器电路设计，两款芯片都可以稳定的支持 `921600` 波特率通信。

![](./Images/PCB-3D-1.png)

![](./Images/PCB-3D-2.png)

## 设计概要

1. 板载 `RXD` 和 `TXD` 的信号读写指示灯；
2. 引出了包括**串口硬件流控信号线**在内的全部片上资源；
3. 增加 **1206** 封装的**自恢复保险丝**，为后级电路提供短接保护；
4. 使用 **16 Pin** 的 **USB Type-C** 接口，并且采用了 PCB 拼板设计；
5. 预留有 `1mm` 的固定螺丝孔，便于安装至 3D 打印外壳，或者搭建成套的产品原型；
6. 通过为 **UINIO-USB-UART-CH343P** 的 `VIN` 引脚提供参考电压，可以调整 UART 的信号电平幅值。

## 参考技术文档

[UinIO.com 电子技术实验室](http://uinio.com/) 为 UINIO-USB-UART 开源项目提供了如下一系列技术参考资料：

- [《BOM 交互式物料清单与 PCB 布线在线预览》](http://uinio.com/archives/BOM/UINIO-USB-UART.html)
