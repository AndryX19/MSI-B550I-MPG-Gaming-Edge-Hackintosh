# Hackintosh:
EFI made for MSI B550I MPG (ITX) Gaming Edge / Gaming Edge Max with Opencore bootloader

## System specifications:
| **Component** | **Model** |
| ------------- | --------- |
| CPU | AMD Ryzen 5 5600X |
| RAM | 16GB (2x8GB) DDR4 Crucial Ballistix @3600MHz |
| DGPU | AMD Sapphire Nitro RX 590 8gb |
| Monitor | AOC Q3279WG5B QHD (2k) 75Hz |
| SSD | NVMe Samsung 970 Evo 1TB |
| Audio | Realtek ALC S1200A |
| Wireless | Intel AX200 (wifi+bluetooth) |
| Ethernet | Realtek 8125B 2.5G LAN |

**Current OpenCore version: 0.7.6**

## Used macOS version:
 - Big Sur 11.6

Probably you can also boot catalina and monterey (require newer bluetooth kext). Not tested

## What Works:
 - Wi-Fi
 - Bluetooth
 - Ethernet
 - dGPU (mine supported natively)
 - Audio
 - All usb
 - Sleep/Wake up

## What Doesn't Work:
 - Seem nothing

## BIOS setting:
 - Secure Boot           -> Disabled
 - CFG Lock              -> Disabled
 - SATA Mode             -> AHCI
 - Above 4G Decoding     -> Enabled 
 - EHCI/XHCI Hand-off    -> Enabled
 - SVM                   -> Enabled
 - CSM                   -> Disabled
 - Resizable BAR Support -> Disabled

**Use the latest stable BIOS (v.7C92v17). Beta ones (e.g. v.7C92v181 (Beta version)) cause bootloop issues, no fix at the moment. If you have upgraded to the beta version you can safely downgrade with m-flash.**
 		
## Installation:
 - See Dortania guide -> https://dortania.github.io/OpenCore-Install-Guide/installer-guide/
 - Generate yours personal SMBIOS data for iMacPro1,1
 - with TextEdit put the generated MLB, SerialNo. and UUID in PlatformInfo section of config.plist in OC folder
 - Use my EFI for boot and install macOS

That's all.
