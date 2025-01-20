# Hackintosh, Dell Latitude 3400, i7 8565U, UHD 620 + Fenvi BCM94360NG

![Overview](https://github.com/danino666/EFI-Latitude-3400-i7-8565U-UHD-620/blob/main/img/Overview.png)

**Release date**: 19/01/2025

## Complete hardware specs
|Item|Description|
|-|:-------|
|**Type**|Notebook|
|**Mobo**|Dell Latitude 3400|
|**CPU**|Intel Core i7-8565U - 8th Gen Whiskey Lake|
|**RAM**|2x16Gb DDR4 2400Mhz|
|**iGPU**|Intel(R) UHD Graphics 620 (1 GB) - 8086 3EA0|
|**Audio**|Intel Cannon Point-LP PCH|
|**ETH**|Realtek PCIe GbE Family Controller [RTL8111]|
|**WLAN+BT**|Fenvi BCM94360NG [Airdrop]|
|**Storage**|PC SN520 NVMe WDC (256 GB)|
|**Trackpad**|HID/PS2 - VEN_DELL&DEV_08BC|
|**Keyboard**|Standard Keyboard PS/2|
|**Ports**|USB-C (PD+DP-AltMode), 2xUSB3.1, 1xUSB2.0, HDMI, microSD, Multi-Jack, DC|
|**SMBIOS**|MacBookPro15,2|
|**macOS**|Sequoia 15.2|
|**Bootloader**|OpenCore 1.0.3|

## What works
- Bluetooth (4.0, LE, Handoff) [out-of-the-box, no kext needed]
- WLAN (BCM94360 need kexts IOSkywalkFamily and kernel-block.plist)
- Ethernet (RealtekRTL8111.kext)
- HDMI, DisplayPort Alt Mode (all with sound, but no volume adjustment)
- Graphics acceleration
- USB ports including USB-C mapped, working after sleep 
- TrackPad with gestures (visible as Magic Trackpad 2)
- Audio, with speaker and microphone support
- Sleep
- TouchPad buttons
- Multi-Jack (both cold- and hotplug)
- Dedicated brightness control keys (use Fn+S/Fn+B instead) (F11/12 is working too)

## What doesn't work
- MicroSD card reader (Not tested)
- 720p WebCam (Not tested)
- *Hibernation (none of Hackintoshes can do that)*
- *Fingerprinting (needs a real T2 chip to work)*


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
