## Jetson Nano Tx2 Tx1

Nvidia Jetson 开发板折腾笔记



一、Jetson Nano

###### **技术规格**

| GPU      | NVIDIA Maxwell™ 架构，配备 128 个 NVIDIA CUDA® 核心 |
| -------- | --------------------------------------------------- |
| CPU      | 四核 ARM® Cortex®-A57 MPCore 处理器                 |
| 内存     | 4 GB 64 位 LPDDR4                                   |
| 存储空间 | 16 GB eMMC 5.1 闪存                                 |
| 视频编码 | 4K @ 30 (H.264/H.265)                               |
| 视频解码 | 4K @ 60 (H.264/H.265)                               |
| 摄像头   | 12 通道（3x4 或 4x2）MIPI CSI-2 DPHY 1.1 (1.5 Gbps) |
| 连接     | 千兆以太网                                          |
| 显示器   | HDMI 2.0 或 DP1.2 \| eDP 1.4 \| DSI (1 x2) 2 同步   |
| UPHY     | 1 x1/2/4 PCIE、1x USB 3.0、3x USB 2.0               |
| I/O      | 1x SDIO/2x SPI/6x I2C/2x I2S/GPIO                   |
| 尺寸     | 69.6 mm x 45 mm                                     |
| 规格尺寸 | 260 针边缘连接器                                    |



1、性能

算力：472 GFLOP

并行运行多个神经网络

处理多个高分辨率传感器

家用机器人

智能网关

适合做网络硬盘录像机NVR

功率：5-10瓦  使用树莓派电源就行了

2、上手过程

f1下载镜像：

<https://developer.nvidia.com/embedded/downloads>

f2下载写卡软件

<https://www.balena.io/etcher/>

f3插入内存卡开机

设置swap空间，最好4G

（这里很重要，如果不设置变异dlib库会直接卡死）

3、开发者

官方手册：

<https://docs.nvidia.com/jetson/l4t/index.html>



二、Jetson Tx1