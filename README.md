# SAMSUNG-35X0AA-Hackintosh
## 版本
OpenCore：0.7.2

macOS：macOS Big Sur 11.5.2（20G95）

## 配置信息
CPU：Intel i5-8250U

GPU：Intel UHD Graphice 620 + NVIDIA GeForce MX110

RAM：Samsung DDR4 2400MHz 4 GB + SK Hynix DDR4 2400Mhz 8 GB

SSD：SAMSUNG 128GB MZNLN128HAHQ-000

HDD：Barracuda 1TB ST1000LM048-2E7172

Audio：Realtek ALC256

Network：RTL810x/8139 Family Fast Ethernet NIC

## 正常工作
核心显卡、声卡、有线网卡、USB、电源管理、CPU变频、电池电量显示、睡眠、唤醒、摄像头、麦克风、键盘

## 不工作
独立显卡、蓝牙、WIFI、触控板

## 更新日志
说明：当前引导支持 Mojave、Catalina、Big Sur（10.14～11.x）。暂不考虑适配 macOS Monterey（12）开发者预览版（Beta 版），等待秋季发布正式版。

### 2021-08-16

1、定制 USBPorts.kext 驱动所有 USB 并内建。

2、关闭部分无用内核Kext驱动。

### 2021-08-12

1、升级 OpenCore 0.7.2 正式版。

2、例行升级 kext 版本（AppleALC、Lilu、NVMeFix、VirtualSMC、WhateverGreen、ECEnabler）。

3、启用 OpenCore 默认主题模式引导。

4、添加缓冲帧补丁。

5、模拟机型为MacBookPro14,2。

### 2021-08-10

1、基于 OpenCore 0.7.1 正式版进行EFI引导制作。
