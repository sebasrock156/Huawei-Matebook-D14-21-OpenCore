# Huawei Matebook D14 (2021) Hackintosh with OpenCore

![progress](https://img.shields.io/badge/Progress-Under_development-red.svg)
![installation](https://img.shields.io/badge/installation-working-green.svg)
[![Acer OSX](https://img.shields.io/badge/AcerHackintosh-available_here-violet.svg)](https://github.com/sebasrock156/Acer-E5-572-TMP246-OpenCore)
[![Asus OSX](https://img.shields.io/badge/AMDOSX-alpha_here-violet.svg)](https://github.com/sebasrock156/Asus-X555QA-Hackintosh)


This is a "big" project to bring MacOS OSes for these laptops with OpenCore Bootloader, for more information, click on "More info of **MacOS Version** below:

**More info of MacOS BigSur:**

//[![MacOS HighSierra](https://i.imgur.com/GMurHMa.png)](https://github.com/sebasrock156/Asus-X555QA-Hackintosh/tree/High-Sierra)

**Status:** ✅❌ In-process, for now, doesn't fix some things 💻

**Notes for future:** I'll try to change to Opencore Bootloader. 

---

**More info of MacOS Monterey:**

//[![MacOS Catalina](https://i.imgur.com/s61fRsN.png)](https://github.com/sebasrock156/Asus-X555QA-Hackintosh/tree/Catalina)

**Status:** ❌ In-process 💻

**Notes for future:** Trying this work, based on AMD FX 8xxx model. 

---

**More info of MacOS Ventura:**

//[![MacOS BigSur](https://i.imgur.com/SPRlO8S.png)](https://github.com/sebasrock156/Asus-X555QA-Hackintosh/tree/BigSur)

**Status:** ❌ In-process 💻

**Notes for future:** If work in Catalina, might work on BigSur, based on AMD FX 8xxx model. 

---

**More info of MacOS Sonoma:**

//[![MacOS Monterey](https://i.imgur.com/yuAgctK.png)](https://github.com/sebasrock156/Asus-X555QA-Hackintosh/tree/Monterey)

**Status:** ❌ Next version to port 💻


---


**Let's go with my hardware**:
---

Hardware | Model
--- |:--:
![processor](https://i.imgur.com/H44zEoW.png) | AMD A10 9620P/A12 9700P/FX 9800P, 4 cores/threads@3,0/3,4/3,6Ghz
![igpu](https://i.imgur.com/7TZmF2e.png)| Radeon R5/R7 512MB/1GB VRAM@720/758Mhz (Not supported)
![audio](https://i.imgur.com/SCKuD0b.png) | Conexant CX20752
![dgpu](https://i.imgur.com/7TZmF2e.png) | (Not available, try to replace for any MB with some Radeon dGPU)
![wlan](https://i.imgur.com/dUwPhAC.png) | Realtek RTL8821AE+Bluetooth 4.0 (Not supported)
Ethernet | Realtek RTL8111
![ddr4](https://i.imgur.com/g3gLTem.png) | Samsung 8GB CL22@2133Mhz (in-build) + Crucial 8GB CL19@2400Mhz (external)
![ssd](https://i.imgur.com/Jixm0UG.png) | Crucial BX500 SSD 480GB (TLC SMI2258XT Controller)
---

<details>
 
**Now, some minimum hardware recommendations**:

---

Hardware | Model
--- |:--:
RAM | Any Samsung, Crucial or Kingston DDR4 8GB (in-unique slot).
Audio Card | Any Realtek and some Conexant Audio Cards.
WLAN Card | Any Intel network card, some Broadcom network cards, and few Qualcomm/Atheros network cards).
SATA Drive	| Any Solid State Drive (SSD) with 240GB or more of storage.
IDE Drive | Add a caddy for SATA Output, then, I recommend any Hard Disk with 500GB/1000GB of storage.
---
 
</details>


## Misc:
This is based on Olarila RAW MacOS Images.
In future, I'll try use Opencore for newer versions.
