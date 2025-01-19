# Hackintosh, Dell Latitude 3400, i7 8565U, UHD 620 + Fenvi BCM94360NG

**Current OpenCore**: 1.0.3
<br>
**Release date**: 19/01/2025

## Complete hardware specs
|Item|Description|
|-|:-------:|
|Type|Notebook|
|Mobo|Dell Latitude 3400|
|CPU|Intel Core i7-8565U - 8th Gen Whiskey Lake|
|Memory|2x16Gb DDR4 2400Mhz|
|dGPU/iGPU|Intel(R) UHD Graphics 620 (1 GB) - 8086 3EA0|
|Audio Codec|Intel Cannon Point-LP PCH|
|Ethernet|Realtek PCIe GbE Family Controller [RTL8111]|
|Wireless/BT|Fenvi BCM94360NG [Airdrop]|
|Storage|PC SN520 NVMe WDC (256 GB)|
|Trackpad|HID/PS2 - VEN_DELL&DEV_08BC|
|Keyboard|Standard Keyboard PS/2|
|Re-SIZE Bar Support|Resizable BAR    Disabled|
|macOS|Sequoia 15.2|

## What works
- All features

## What doesn't work
- Fingerprinting is not possible because macOS needs a real T2 chip to work

## Kexts used:
- AMFIPass.kext
- AppleALC.kext
- BrightnessKeys
- CpuTscSync
- ECEnabler
- IO80211FamilyLegacy
- IOSkywalkFamily
- Lilu.kext
- NVMeFix
- RealtekRTL8111
- RestrictEvents
- SMCBatteryManager
- SMCDellSensors
- SMCLightSensor
- SMCProcessor.kext
- SMCSuperIO.kext
- USBMap.kext
- VirtualSMC.kext
- VoodooI2C
    - VoodooGPIO
    - VoodooI2CServices
- VoodooI2CHID
- VoodooInput
- VoodooPS2Controller
    - VoodooPS2Keyboard
- WhateverGreen.kext

## References/Credits
- [Laptop Coffee Lake and Whiskey Lake](https://dortania.github.io/OpenCore-Install-Guide/config-laptop.plist/coffee-lake.html)
- [EFI.Opencore.NoteBook.Coffee.Lake.Whiskey.Lake.MOD](https://olarila.com/files/?dir=OPENCORE.MOD1)
- [Universo Hackintosh](https://github.com/luchina-gabriel/BASE-EFI-INTEL-8THGEN-COFFEE-LAKE-PUBLIC)
    - [pack-activate-wifi-bt-BCM94360-sequoia-v3](https://youtu.be/wH7S2ano-ac?si=OgVS7jBvdCaL3S8z)
