# UINIO-USB-UART-CH343 串口调试器

[**UINIO-USB-UART-CH343**](https://gitee.com/uinika/UINIO-USB-UART) 是一款基于[**苏州沁恒 CH343P**](https://www.wch.cn/products/CH343.html) 芯片的 **USB** 转 **UART** 的开源串口调试器，该款芯片采用了小尺寸的 `QFN16` 封装，可以稳定支持 `921600` 波特率的 UART 串口通信。

![](./Images/PCB-3D-1.png)

![](./Images/PCB-3D-2.png)

## 设计概要

1. 板载 `RXD` 和 `TXD` 的信号传输状态指示灯；
2. USB 信号线上并入了两枚 **TVS** 瞬态电压抑制二极管；
3. 引出了包括**串口硬件流控信号线**在内的全部片上资源；
4. 为 `3.3V` 输出提供了**自恢复保险丝**和**二极管**组成的防反接保护电路；
5. 预留有 `2mm` 的固定螺丝孔，便于安装至 3D 打印外壳，或者搭建成套的产品原型；
6. 板载的 `VIN` 引脚用于接入外部的参考电压，从而调整当前 UART 信号输出的电平幅值。

## 参考技术文档

[UinIO.com 电子技术实验室](http://uinio.com/) 为 **UINIO-USB-UART-CH343** 开源项目提供了如下一系列技术参考资料：

- [《UINIO-DAPLink 核心板原理图》](http://uinio.com/my/works/UINIO-USB-UART-CH343/UINIO-USB-UART-CH343-Schematic.pdf)
- [《交互式 BOM 物料清单与 PCB 版图在线预览》](http://uinio.com/my/works/UINIO-USB-UART-CH343/UINIO-USB-UART-CH343-BOM.html)
