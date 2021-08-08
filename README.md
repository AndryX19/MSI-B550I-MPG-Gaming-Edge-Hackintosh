# Hackintosh
OpenCore EFI made for MSI B550I MPG (ITX)   Gaming Edge / Gaming Edge Max

## Specification
| **Component** | **Model** |
| ------------- | --------- |
| CPU | AMD Ryzen 5 5600X |
| RAM | 16GB (2 x 8GB) DDR4 Crucial Ballistix 3600MHz (XMP) |
| DGPU | AMD Sapphire Nitro RX590 8gb |
| Display | AOC QHD (2k) 75Hz |
| NVMe 1 | Samsung 970 Evo 1TB |
| Audio | Realtek ACL1200 |
| Wireless | Intel AX200 (wifi+bluetooth) |
| Ethernet | Realtek 8125B 2.5G LAN |

**Current OpenCore version: 0.7.1**

## Compatible macOS versions:
 - Big Sur (11.5) (In use)
 - Catalina (10.15) (I haven't tried it)

## What Works:
 - Wi-Fi
 - Bluetooth
 - Ethernet
 - dGPU (native)
 - Audio
 - All usb
 - Sleep/Wake up

## What Doesn't Work:
 - Tell me if something doesn't

## BIOS setting:
 - Secure Boot           > Disabled
 - CFG Lock              > Disabled
 - SATA Mode             > AHCI
 - Above 4G Decoding     > Enabled 
 - EHCI/XHCI Hand-off    > Enabled
 - SVM                   > Enabled
 - CSM                   > Disabled
 - Resizable BAR Support > Disabled
 		
## Installation
 - See Dortania guide > https://dortania.github.io/OpenCore-Install-Guide/installer-guide/
 - Generate yours personal SMBIOS data for iMacPro1,1
 - with TextEdit put the generated MLB, SerialNo. and UUID in PlatformInfo section of config.plist in OC folder
 - Use my EFI for boot and install macOS

That's all, good hack.
