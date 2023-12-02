# Hackintosh OpenCore MSI MPG Z490 Gaming Plus + dGPU

**# Specifications:**
* CPU: Intel Core i9-10850k
* GPU: AMD ASUS STRIX RX 5700XT (aka W5700X)
* Motherboard: **MSI MPG Z490 Gaming Plus**
                 Audio: Realtek® ALC1200-VD1
                 Ethernet: Realtek® RTL8125B-CG 2.5G LAN Controller
* RAM: 4x GSkill DDR4 8Gb 4133MHz
* WIFI/BT: Fenvi T919
* NVME: ADATA SX8200NP - MacOS
* NVME: Samsung 970 EVO - Windows

**# Versions:**
* OpenCore: 0.9.6
-  Drivers: HfsPlus, OpenCanopy, OpenRuntime
-  Kexts: AppleALC (1.8.7),
-  Lilu (1.6.7),
-  LucyRTL8125Ethernet (1.1.0),
-  NVMeFix (1.1.1),
-  RadeonSensor (1.3.0),
-  SMCRadeonGPU (1.3.0),
-  SMCProcesor|SMCSuperIO|VirtualSMC (1.3.2),
-  WhateverGreen (1.6.6)

OpenCore setup was made according to https://dortania.github.io/OpenCore-Install-Guide/

**# Working:**
- [x] Intel UHD Graphics 630
- [x] Audio (Layout-id=7) - modified AppleALC plist due to issue with sound after booting from Windows
- [x] Ethernet
- [x] CPU power management
- [x] USB ports

- **GeekBench6** CPU Singe 1698, Multi 10113
- **GeekBench6** GPU Metal 102678

# SMBIOS:
iMac20,2
