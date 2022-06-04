# MacOS on ThinkPad T490

This repository is made to help run macOS on a ThinkPad T490. Currently running 11.6.2 since this isn't the main OS on my computer anymore and I don't really have the time to update it.

This should help you get started on hackintoshing and any updates can be applied later. I may occasionally update this repo if I find the time but there's no guarantee.

I recommend going through the [Opencore install guide](https://dortania.github.io/OpenCore-Install-Guide/) once to fully understand everything that is going on here. 

Keep in mind that you have to generate your own serial numbers and ID's and stuff using [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS) (TIP: Use MacBookPro15,4)

**NOTE:** This is only for you to get started. You will have to do your own post-installation/updates/configurations

**CAUTION:** Test drive this configuration once using a USB flash drive before you move it to the main EFI partition. I am not responsible for any damages incurred.

# **Hardware Info:**

|**Component**|**Model**|
|:-|:-|
|**CPU**|Intel Core i5-8265u|
|**GPU**|Intel HD Graphics 620|
|**RAM**|16GB 3200 MHz DDR4|
|**Storage** |512GB SAMSUNG MZVLB512HBJQ-000L7|
|**WiFi/Bluetooth**|Intel Wireless AC-9560|
|**Touchpad**|Synaptics|
|**Display**|14" 1920x1080 IPS Non-Touch|
|**Camera**|720p HD w/ Privacy Shutter|
|**Battery**|Single 50 Wh|

# What Works

* Keyboard (including all media keys)

* Trackpad and TrackPoint with clicky buttons

* Battery indicator

* Display Auto-Brightness

* HDMI video and audio (up to 4K 30Hz because of HDMI 1.4 limitations)

* Audio

* Ethernet

* iCloud Services (iMessage, FaceTime, iCloud Drive)

* GPU Acceleration

* Camera

* Microphone

* Sleep/Wake

* Trackpad with gestures

* CPU Power Management

* Handoff, Continuity

* AirPlay

* FileVault

* DRM Content (Netflix, Apple TV+)

* Fan Control using YogaSMC

# What doesn't work

* USB-C Audio

* SD Card Reader (not useful to me)

* AirDrop

# Not Tested

* Sidecar

# Credits

* [Acidanthera](https://github.com/acidanthera)

* [Opencore Install Guide](https://dortania.github.io/OpenCore-Install-Guide/)

* [CorpNewt](https://github.com/corpnewt)

* [YogaSMC](https://github.com/zhen-zen/YogaSMC)

* [Yusifsalam's t490-macos repo](https://github.com/yusifsalam/t490-macos)
