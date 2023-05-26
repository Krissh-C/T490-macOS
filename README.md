# Updates
Released the latest version for 13.4 with OC 0.9.2

# Issues
For any issues, please open an issue or check if there's a solution already available in the issues section. Issues with solutions will be under closed issues. 

# macOS on ThinkPad T490
This repository is made to help run macOS on a ThinkPad T490.

This should help you get started on hackintoshing and any updates can be applied later. I may occasionally update this repo if I find the time but there's no guarantee.

I recommend going through the [Opencore install guide](https://dortania.github.io/OpenCore-Install-Guide/) once to fully understand everything that is going on here.

**NOTE**: macOS will not work with Samsung PM981/a drives out of the box. Suggest replacing or not using the drive with macOS.

Keep in mind that you have to generate your own serial numbers and ID's and stuff using [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS) if you're doing a fresh install. Use your old ones from your old config.plist if you're just changing EFI's (TIP: Use MacBookPro15,4 but I've included that in the plist)

This hakcintosh will be complete only with [YogaSMC](https://github.com/zhen-zen/YogaSMC). After installing, please use the app and the system preferences add on as it enables some features for this to be complete.

**CAUTION**: Test drive this configuration once using a USB flash drive before you move it to the main EFI partition. I am not responsible for any damages incurred.

# Hardware Info

|**Component**|**Model**|
|:-|:-|
|**CPU**|Intel Core i5-8265u|
|**GPU**|Intel UHD Graphics 620|
|**RAM**|16GB 2400 MHz DDR4|
|**Storage (Windows)**|512GB SAMSUNG MZVLB512HBJQ-000L7 |
|**Storage (macOS)**|512GB External WD Blue |
|**WiFi/Bluetooth**|Intel Wireless AC-9560 |
|**Touchpad**|Synaptics|
|**Display**| 14" 1920x1080 IPS Non-Touch |
|**Camera**| 720p HD w/ Privacy Shutter |
|**Battery**| Single 50 Wh |

# Screenshots
![aboutmac](https://user-images.githubusercontent.com/117280851/207616017-8975c9c1-efeb-4435-8456-18c589f0d8a8.png)

# What Works
- Keyboard (including all media keys)
- Trackpad and TrackPoint with clicky buttons
- Battery indicator
- Display Auto-Brightness
- HDMI
- Audio (Speakers, Headphone Jack, Bluetooth and USB-C headsets)
- Bluetooth
- Ethernet
- iCloud Services (iMessage, FaceTime, iCloud Drive)
- GPU Acceleration
- Camera
- Microphone
- Sleep/Wake
- Trackpad with gestures
- CPU Power Management (suggest making your own using [CPUFriendFriend](https://github.com/corpnewt/CPUFriendFriend))
- Battery Indicator
- Handoff, Continuity
- AirPlay
- FileVault
- DRM Content (more info below)
- Fan Control using [YogaSMC](https://github.com/zhen-zen/YogaSMC)

# What doesn't work
- SD Card Reader
- AirDrop
- Thunderbolt
- DRM on Safari, Apple TV, Quicktime, etc (Eg. For Netflix, use Chrome/Firefox/Your choice)

# Not Tested
- USB-C Video (audio works)
- Sidecar
- Universal Control

# Credits
- [Acidanthera](https://github.com/acidanthera)
- [Opencore install guide](https://dortania.github.io/OpenCore-Install-Guide/)
- [CorpNewt](https://github.com/corpnewt)
- [YogaSMC](https://github.com/zhen-zen/YogaSMC)
- [Yusifsalam's t490-macos repo](https://github.com/yusifsalam/t490-macos)
