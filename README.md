# SAMSUNG-35X0AA-Hackintosh
## Version
OpenCore：0.7.3

macOS：macOS Big Sur 11.6（20G165）

说明：当前引导支持 Mojave、Catalina、Big Sur（10.14～11.x）。暂不考虑适配 macOS Monterey（12）开发者预览版（Beta 版），等待秋季发布正式版。

## Configuration
| Specifications | Detail | Working |
| :------------: | :------: | :--------: |
| Model | SAMSUNG-35X0AA | ✅ |
| Processor | Intel Core Intel i5-8250U @ 1.60Ghz | ✅ |
| Memory | 16GB Samsung DDR4 2400Mhz | ✅ |
| SSD | SAMSUNG MZNLN128HAHQ 128GB | ✅ |
| HDD | ST1000LM048 1TB | ✅ |
| iGPU | Intel UHD Graphice 620 | ✅ |
| dGPU | NVIDIA GeForce MX110 | 🚫 |
| Sound Card | Realtek ALC256 | ✅ |
| Camera | Web Camera | ✅ |
| Ethernet Card | Realtek RTL8106E | ✅ |
| Wireless Card | Qualcomm Atheros QCA9377 | 🚫 |
| Keyboard | Keyboard | ✅ |
| TouchPad | Touchpad ATML3000 | 🚫 |

## BIOS Configuration
|  Configuration |   |
| ------------ | ------------ |
|  **Advanced**  |   |
|  Touch Pad Mouse | On  |
|  Touch Pad S3 Wake-up | Off  |
|  USB S3 Wake-up |  Off |
|  **Security** |   |
|  Password | Off  |
|  **Boot** |   |
|  Secure Boot Control   | Off |
|  OS Mode Selection   | UEFI OS |
|  Fast BIOS Mode   | Off |

## Updates

- 2021-09-30

  1、升级 OpenCore 0.7.3 正式版。

  2、例行升级 kext 版本（AppleALC、Lilu、VirtualSMC、WhateverGreen）。
  
  此次版本为优化版，升级此版本建议清空nvram（使用 Hackintool 或进入 OC 启动菜单执行 Reset Nvram）。
<details>
<summary>2021-08-16</summary>
1、定制 USBPorts.kext 驱动所有 USB 并内建。
<br>
2、关闭部分无用内核Kext驱动。
</details>
  
<details>
<summary>2021-08-12</summary>
1、升级 OpenCore 0.7.2 正式版。
<br>
2、例行升级 kext 版本（AppleALC、Lilu、NVMeFix、VirtualSMC、WhateverGreen、ECEnabler）。
<br>
3、启用 OpenCore 默认主题模式引导。
<br>
4、添加缓冲帧补丁。
<br>
5、模拟机型为MacBookPro14,2。
</details>

<details>
<summary>2021-08-10</summary>
1、基于 OpenCore 0.7.1 正式版进行EFI引导制作。
</details>
