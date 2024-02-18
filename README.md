# Huawei Matebook D14 (2021) Hackintosh with OpenCore

![progress](https://img.shields.io/badge/Progress-Under_development-red.svg)
![installation](https://img.shields.io/badge/installation-working-green.svg)
[![LegacyAcer OSX](https://img.shields.io/badge/LegacyAcerHackintosh-available_here-violet.svg)](https://github.com/sebasrock156/Acer-Aspire-5749-Hackintosh)
[![EFIAcer OSX](https://img.shields.io/badge/EFIAcerHackintosh-available_here-violet.svg)](https://github.com/sebasrock156/Acer-E5-572-TMP246-OpenCore)
[![Asus OSX](https://img.shields.io/badge/oldAMDOSX-alpha_here-violet.svg)](https://github.com/sebasrock156/Asus-X555QA-Hackintosh)

**⚠ WARNING ⚠:  I'm working with another laptop for now, so, this project is stopped** 


This is a "big" project to bring MacOS OSes for these laptops with OpenCore Bootloader, for more information, click on "More info of **MacOS Version** below:

**More info of MacOS BigSur:**

[![MacOS BigSur](https://i.imgur.com/lhFb24x.png)](https://github.com/sebasrock156/Huawei-Matebook-D14-21-OpenCore/tree/BigSur)

**Status:** 👨🏾‍🏭 In development (test with [First Release EFI](https://github.com/sebasrock156/Huawei-Matebook-D14-21-OpenCore/releases) )💻

**To do:** Try fix Wi-Fi with HeliPort, fix 3D Acceleration when is possible.

---


**More info of MacOS Monterey:**

[![MacOS Monterey](https://i.imgur.com/hVAkcmx.png)](https://github.com/sebasrock156/Huawei-Matebook-D14-21-OpenCore/tree/Monterey)

**Status:** 👨🏾‍🏭 In development (test with [Second Release EFI](https://github.com/sebasrock156/Huawei-Matebook-D14-21-OpenCore/releases) )💻

**To do:** Fix 3D Acceleration when is possible.

---


**More info of MacOS Ventura:**

[![MacOS Ventura](https://i.imgur.com/7qS5AMA.png)](https://github.com/sebasrock156/Huawei-Matebook-D14-21-OpenCore/tree/Ventura)

**Status:** 👨🏾‍🏭 In development (test with [Second Release EFI](https://github.com/sebasrock156/Huawei-Matebook-D14-21-OpenCore/releases) )💻

**To do:** Fix 3D Acceleration when is possible.

---


**More info of MacOS Sonoma:**

[![MacOS Sonoma](https://i.imgur.com/enkO7nT.png)](https://github.com/sebasrock156/Huawei-Matebook-D14-21-OpenCore/tree/Sonoma)

**Status:** 🚧 Tested, but abbandoned for now (EFI boots to OC Menu, but WONT BOOT TO INSTALLER)💻


---


---

Hardware | Model
--- |:--:
![motherboard](https://i.imgur.com/1bfb9L6.png) | Huawei BOD-WXX9 (Tiger Lake-U)
![bios](https://i.imgur.com/98P6ntE.png) | Insyde H20 v2.29 (by Huawei)
![processor](https://i.imgur.com/BzXF1mf.png) | Core i5 (11th Gen) 1135G7 4 Cores/8 Threads@2,42Ghz
![igpu](https://i.imgur.com/HS92HLo.png)| Xe Graphics GT2 1,2GB VRAM @1,4GHz (Not supported officially)
![audio](https://i.imgur.com/Xpsn2zb.png) | Everest ESSX8336 (Usually, Apple doesn't support I2C Audio Cards)
![wlan](https://i.imgur.com/9eDLwo9.png) | 6 Wi-Fi/Bluetooth AX201 (Supported with AirportItlwm)
![lpddr4](https://i.imgur.com/1VtslzT.png) | Samsung 8GB(4x2) LPDDR4@2667Mhz (in-build)
![nvme](https://i.imgur.com/J9Q96yY.png) | Phison 311CD0 NVMe 512GB (TLC PS5013 Controller)
Fingerprint | Goodix USB FP 5125 (Not support)
Webcam | OmniVision OV9734 HD Webcam (Keyboard in-build)
---


## Misc:
This is based on Olarila RAW MacOS Images.
In future, I'll try use Opencore for newer versions.
