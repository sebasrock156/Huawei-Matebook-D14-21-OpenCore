# [PRE-ALPHA WIP] Huawei Matebook D14 (2021) Hackintosh Ventura (13.0 - 13.4) with OpenCore

![img](https://i.imgur.com/MEjR3Gt.png)

⚠️**WARNING**: For now, Post-Installation works weird ⚠️

---

Hardware | Model
--- |:--:
![processor](https://i.imgur.com/BzXF1mf.png) | 1135G7 4 Cores/8 Threads@2,42Ghz
![igpu](https://i.imgur.com/HS92HLo.png)| Xe Graphics 1,2GB VRAM @1,4GHz (Not supported)
![audio](https://i.imgur.com/Xpsn2zb.png) | Everest ESSX8336 (Not supported)
![wlan](https://i.imgur.com/9eDLwo9.png) | AX201
![lpddr4](https://i.imgur.com/1VtslzT.png) | 8GB(4x2) LPDDR4@2667Mhz (in-build)
![nvme](https://i.imgur.com/J9Q96yY.png) | 311CD0 NVMe 512GB (TLC PS5013 Controller)
---

### Works:
---
<details>

- Opencore 0.9.3 ✅ 

- Installer Boot ✅ (Installation on: NVMe SSD: ~20/25 minutes; SATA3 SSD: ~28/30 minutes)

- System Boot ✅

- USB Ports ✅ (Now all works).

- VoodooPS2Controller/Keyboard ✅ (Works).
  
- VoodooI2CHID/Touchpad ✅ (Recognize the GXTP7863 sensor weird, works but skips some screen pixels).

- Camera ✅ (works perfectly)

- Battery charging and stats ✅

- Screen ✅ (1080x1920)

- Wi-Fi ✅ (altrough is some slow to connect)
  
- Bluetooth ✅ (Sound devices have some cuts, mouses/keyboards works pretty well, Android devices works/iOS devices are detected but AirDrop is broken).


 
</details>



### Not works:
---

<details>

- Audio Card ❌ (It's recognized as Tiger-Lake SST/Comet-Lake SST, but isn't enabled)

- Microphone ❌ (It is not recognized)

- HDMI ❌ (Doesn't work without 3D Acceleration)

- Screen Backlit ❌ (Doesn't work without 3D Acceleration)

- Fingerprint Scanner ❌ (Don't exist some Goodix kext for MacOS; use NoTouchID kext for disable it)

</details>

