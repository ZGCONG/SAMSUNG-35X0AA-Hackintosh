# SAMSUNG-35X0AA-Hackintosh
EFI for SAMSUNG 35X0AA (i5-8250U) By @ZGCong

## 当前版本（Version）
* OpenCore：1.0.4
* 当前引导支持系统：Big Sur、Monterey、Ventura、Sonoma、Sequoia（11.0～15.x）
* ⚠️注意：升级此版本建议使用 Hackintool 或进入 OC 启动菜单执行 Reset Nvram（Recovery 模式和 Reset NVRAM 均为隐藏功能，可在 OpenCore 引导界面敲击一下空格，即可出现）

## 配置（Specification）
- **Processor**: Intel Core Intel i5-8250U @ 1.60Ghz (Kaby Lake R)
- **IGPU**: Intel UHD Graphice 620 (共享显存 2048MB)
- **dGPU**: NVIDIA GeForce MX110 (无解)
- **Memory**: 4GB Samsung DDR4 2400Mhz + 32GB Kingston DDR4 3200MHz
- **Wi-Fi**: Qualcomm Atheros QCA9377 (无解)
- **Ethernet**: Realtek RTL8106E
- **Bluetooth**: Qualcomm Atheros QCA9377 (无解)
- **Audio**: Realtek ALC256 
- **Touchpad**: ATML3000 (无解)
- **SSD Storage**: 256GB SK hynix SC311 M.2 SATA
- **HHD Storage**: 1TB WDS100T2B0A SATA
- **WebCam**: USB 2.0 Camera 
- **Battery**: 43 Wh Battery

## BIOS 设置（BIOS Settings）
- 「Advanced」-「Touch Pad Mouse」-「On」
- 「Advanced」-「Touch Pad S3 Wake-up」-「Off」
- 「Advanced」-「USB S3 Wake-up 」-「Off」
- 「Security」-「Password」-「Off」
- 「Boot」-「Secure Boot Control」-「Off」
-  「Boot」-「OS Mode Selection」-「UEFI OS」
-  「Boot」-「Fast BIOS Mode」-「Off」 

## 更新日志（Change Log）

### 2025-04-19，本次更新内容：
1. 升级 OpenCore 1.0.4 正式版
2. 例行升级 kext 版本（AppleALC、CpuTscSync、ECEnabler、Lilu、VirtualSMC、VoodooPS2Controller、WhateverGreen）
3. 添加 macOS 15 系统的支持，支持升级到 macOS 15.4.1 Sequoia 正式版
4. 移除 macOS Mojave、Catalina 的支持，如果安装该系统，请使用上一版 2024-07-15 EFI 引导

### 2024-07-15，本次更新内容：
1. 升级 OpenCore 1.0.0 正式版
2. 例行升级 kext 版本
3. 添加 CpuTscSync 驱动
4. 支持升级到 macOS 14.5 Sonoma 正式版

### 2023-11-13，本次更新内容：
1. 升级 OpenCore 0.9.6 正式版
2. 例行升级 kext 版本
3. 支持升级到 macOS 14.1.1 Sonoma 正式版

### 2023-04-28，本次更新内容：
1. 升级 OpenCore 0.9.3 正式版
2. 例行升级 kext 版本
3. 支持升级到 macOS 14 Sonoma Beta 测试版

### 2023-04-28，本次更新内容：
1. 升级 OpenCore 0.9.1 正式版
2. 例行升级 kext 版本（AppleALC、BrightnessKeys、VirtualSMC、VoodooPS2Controller、WhateverGreen、Lilu）

### 2023-02-13，本次更新内容：
1. 升级 OpenCore 0.8.8 正式版
2. 例行升级 kext 版本（AppleALC、VoodooPS2Controller、WhateverGreen、Lilu）
3. 移除 NVMeFix.kext 驱动

### 2022-12-16，本次更新内容：
1. 升级 OpenCore 0.8.7 正式版
2. 例行升级 kext 版本（AppleALC、VoodooPS2Controller、WhateverGreen）

### 2022-10-26，本次更新内容：
1. 升级 OpenCore 0.8.5 正式版
2. 例行升级 kext 版本（AppleALC、Lilu、VoodooPS2 、WhateverGreen）
3. 支持升级到 macOS 13 Ventura 正式版

### 2022-07-27，本次更新内容：
1. 升级 OpenCore 0.8.2 正式版
2. 例行升级 kext 版本（AppleALC、ECEnabler、Lilu、 NVMeFix 、VirtualSMC、VoodooPS2 、WhateverGreen）
3. 初步支持 macOS 13 Ventura beta 系统

### 2022-04-28，本次更新内容：
1. 升级 OpenCore 0.8.0 正式版
2. 例行升级 kext 版本（AppleALC、Lilu、WhateverGreen、VoodooPS2、VirtualSMC）
3. 优化 kext 顺序

### 2021-12-13，本次更新内容：
1. 升级 OpenCore 0.7.6 正式版
2. 例行升级 kext 版本（AppleALC、Lilu、VirtualSMC）
3. 适配 OC 对 UIScale 的调整
4. 优化 kext 顺序
5. 加载 CPU 原生电源管理
6. SSDT 补丁禁用 dGPU

### 2021-11-22，本次更新内容：
1. 使用 OpenHfsPlus.efi 作为 HFS 文件系统驱动
2. 更新 OpenCore 默认主题素材
3. OpenCore 启动引导调整（取消隐藏辅助条目、允许直接切换 SIP 状态）
4. 去除多余 Tools 工具

### 2021-11-17，本次更新内容：
1. 升级 OpenCore 0.7.5 正式版
2. 例行升级 kext 版本（AppleALC、Lilu、WhateverGreen、VoodooPS2）

### 2021-11-02，本次更新内容：
1. 升级 OpenCore 0.7.4 正式版
2. 升级 HfsPlus 文件系统驱动
3. 例行升级 kext 版本（AppleALC、WhateverGreen、VoodooPS2）

### 2021-09-30，本次更新内容：
1. 升级 OpenCore 0.7.3 正式版
2. 例行升级 kext 版本（AppleALC、Lilu、VirtualSMC、WhateverGreen）

### 2021-08-16，本次更新内容：
1. 定制 USBPorts.kext 驱动所有 USB 并内建
2. 关闭部分无用内核Kext驱动

### 2021-08-12，本次更新内容：
1. 升级 OpenCore 0.7.2 正式版
2. 例行升级 kext 版本（AppleALC、Lilu、NVMeFix、VirtualSMC、WhateverGreen、ECEnabler）
3. 启用 OpenCore 默认主题模式引导
4. 添加缓冲帧补丁
5. 模拟机型为MacBookPro14,2

### 2021-08-10，本次更新内容：
1. 基于 OpenCore 0.7.1 正式版进行EFI引导制作
