# Hackintosh, Dell Latitude 3400, i7 8565U, UHD 620 + Fenvi BCM94360NG

![about-12 3 1](https://user-images.githubusercontent.com/23700365/161353027-9aaeddf5-7457-49a8-b322-4e99ab94c679.png)

**Latest working macOS**: macOS Sequoia 15.2
<br>
**Current OpenCore**: 1.0.3
<br>
**Release date**: 19/01/2025

## Complete hardware specs
|Item|Description|
|-|:-------:|
|Tipo|Notebook|
|Mobo|Dell Latitude 3400|
|CPU|Intel Core i7-8565U - 8th Gen Whiskey Lake|
|Memória|2x16Gb DDR4 2400Mhz|
|dGPU/iGPU|Intel(R) UHD Graphics 620 (1 GB) - 8086 3EA0|
|Audio Codec|Intel Cannon Point-LP PCH|
|Ethernet|Realtek PCIe GbE Family Controller [RTL8111]|
|Wireless/BT|Fenvi BCM94360NG [Airdrop]|
|Storage|PC SN520 NVMe WDC 256GB (256 GB)|
|Trackpad|HID/PS2 - VEN_DELL&DEV_08BC|
|Teclado|Teclado Padrão PS/2|
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

## Thanks/Credits
- [Universo Hackintosh](https://github.com/luchina-gabriel/BASE-EFI-INTEL-8THGEN-COFFEE-LAKE-PUBLIC)
- [pack-activate-wifi-bt-BCM94360-sequoia-v3] (https://youtu.be/wH7S2ano-ac?si=OgVS7jBvdCaL3S8z)
- [EFI.Opencore.NoteBook.Coffee.Lake.Whiskey.Lake.MOD](https://olarila.com/files/?dir=OPENCORE.MOD1)
# EFI-Latitude-3400-i7-8565U-UHD-620
