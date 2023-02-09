# Perfect Hackintosh - Intel Core i3 12100F + RX 5500 XT + SOYO Classic B660M Gaming 2,5Gbps

![About This Mac - Basic](https://user-images.githubusercontent.com/23700365/217338248-c4ab44d8-a511-433c-96db-addc0b632813.png)

# Basic Information

**Latest working macOS**: 13.2
<br>
**Current OpenCore**: 0.8.8
<br>
**Release date**: 08/02/2023

# Hackintosh Specifications
|Item|Description|
|-|:-------:|
|CPU|Intel Core i3 12100F|
|Memory|16GB DDR4 3600Mhz (8Gx2)|
|Storage|NVMe TEAM TM8FPD001T|
|GPU|AMD Radeon RX 5500 XT 8Gb|
|Ethernet|Realtek 2,5Gbps RTL8125B|
|WLAN+Bluetooth|Fenvi T919 - BCM94360|
|Audio|Realtek ALC897 Audio Controller|

### Working features
- All features

### Don't work
- Nothing

### Generate your SMBIOS [Important]

1. Open Apps > GenSMBIOS > GenSMBIOS.command
2. Select Option #3 [Generate SMBIOS]
3. Fill with iMacPro1,1
4. Replace Serial Numbers in config.plist of EFI [PlatformInfo > Generic]

|GenSMBIOS App|config.plist|
|-|:-------:|
|Type:|SystemProductName|
|Serial:|SystemSerialNumber|
|Board Serial:|MLB|
|SmUUID|SystemUUID|
|Apple ROM:|ROM|

## BIOS Settings

BIOS [Versions 5.24 - Agosto/2022]

[Press DEL for ENTER BIOS]

1. Exit > Restore Defaults [YES]
2. Advanced > CPU Configuration > Intel (VMX) Virtualization Technology [ENABLED]
3. Advanced > USB Configuration > XHCI Hand-Off [ENABLED]
4. Advanced > IT8613 Super IO Configuration > Serial Port [DISABLED]
5. Advanced > Graphics Configuration > VT-d [ENABLED]
6. Advanced > Graphics Configuration > Primary Display [PEG Slot]
7. Advanced > Graphics Configuration > Internal Graphics [DISABLED]
8. Advanced > Graphics Configuration > Above 4GB MMIO BIOS Assignament [ENABLED]
9. Advanced > PCI Subsystem Settings > Above 4G Decoding [ENABLED]
10. Startup > Fast Boot [ENABLED]
11. Startup > Full Screen Logo Show [DISABLED]
12. Exit > Save Changes and Reset 

## Hackintosh Creator
- [Gabriel Luchina - Universo Hackintosh](https://luchina.com.br)

## Discord - Universo Hackintosh
- [Access Discord](https://discord.universohackintosh.com.br)
