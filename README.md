



# ASUS TUF Gaming B460 Plus (Wi-Fi) | i9-10850K Vanilla Opencore Hackintosh Build | OS Big Sur.
OpenCore configuration for ASUS TUF Gaming B460M-Plus, Intel core i9 i9-10850K. Vanilla configuration with no additional wi-fi/ bluetooth or video card.
I highly recommend learning how to build your own EFI folder by following the detailing guide from Dortania although this may give you a good starting position or reference. 
Just know you dont need to buy additional WI-FI / Bluetooth / Audio or video cards to get Big Sur working - yo can achieve it all from the mobo.


## Specifications

| Part   | Specs | location |
| ------------- |-------------|-------------|
| Motherboard | ASUS TUF Gaming B460 Plus (Wi-Fi)| |
| CPU      | Core i9-10850K. 3.6GHz    | |
| iGPU      | Intel® UHD Graphics 630     | on i9 CPU |
| dGPU      | no additional graphics card     | on board |
| Audio      | Realtek S1200A codec     | on board |
| Ethernet      | Intel® I219-V 1Gb Ethernet | on board |
| WiFi      | Intel® Wi-Fi 6 AX200     | on board |
|RAM      | Crucial Ballistix BL2K32G32C16U4B 3200 MHz, DDR4, DRAM |
| SSD | Crucial MX300 CT1050MX300SSD1 1 TB Internal SSD |
| Profile |  iMac20,2 |
| MacOS | Big Sur|


## Working/Not working
| Status   | Feature  |
| ------------- |-------------|
| ✅ | Apple TV+, Siri, iTunes, Appstore, Facetime |
|✅  | All USB External Ports (3.0 + 2.0 ) including F-Panel | 
|✅  | Sound + Mic |
|✅  | HDMI (Audio + Graphics) |
|✅  | 2nd monitor on HDMI, avoiding the pink / magento screen |
|✅  | Power Management (800 MHz TFM found in BIOS) |
|✅  | iGPU Stability | 
|✅  | Sleep (also with peripherals plugged in) |
|✅  | Ethernet |
|✅  | Bluetooth |


![Audio](/images/main.png "Audio")
![Audio](/images/audio-by-displayport.png "Audio")
![Audio](/images/wifi.png "Audio")


# Guide
This repo is my journey to get my Hackintosh working... which took weeks. Hopefully it will help you achieve your Hackintosh too. 

## Referenc links:
- [EPI Repo ](https://github.com/akarsh1995/ASUS-TUF-Gaming-B460-Plus-i5-10400-Opencore-Hackintosh-Build).
- [EPI Repo ](https://github.com/sutsurup/MSI-Hackintosh-Build).
- [helpful post ](https://www.tonymacx86.com/threads/success-i5-10400-tuf-b460m-gaming-plus-rx5700-opencore.299418/).
- [EPI Repo ](https://github.com/Pai2Chen/OpenCore-Asus-TUF-B450M-Plus-Gaming/).
- [Kexts ](https://kext.me//).
- [Comet Lake Guide ](https://dortania.github.io/OpenCore-Install-Guide/config.plist/comet-lake.html#starting-point).
- [Pink screen](https://www.reddit.com/r/hackintosh/comments/hjyk5j/how_to_fix_pink_screen_hmdi/)
- [Audio config](https://github.com/acidanthera/AppleALC/wiki/Supported-codecs)
- [Intel on board graphics](https://github.com/acidanthera/WhateverGreen/blob/master/Manual/FAQ.IntelHD.en.md)
- [WIFI](https://openintelwireless.github.io/itlwm/Compat.html#mvm-gen-1-iwm)
- [WIFI guide](https://www.youtube.com/watch?v=eqxOEvil2hA)
- [OpenCore BIOS Settings](https://dortania.github.io/OpenCore-Install-Guide/config.plist/comet-lake.html#cleaning-up)
- [Dortania's OpenCore Install Guide](https://dortania.github.io/OpenCore-Install-Guide/)


this is built from scratch from the Dortania's OpenCore Install Guide and then kexts pilfered from anywhere I could find them - thanks everyone! :)

