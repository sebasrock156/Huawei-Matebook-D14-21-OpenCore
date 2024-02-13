# Huawei Matebook D14 (2021) Hackintosh BigSur (11.5.2 - 11.6.3) with OpenCore

![img](https://i.imgur.com/31RLUxv.png)

---

Hardware | Model
--- |:--:
![processor](https://i.imgur.com/BzXF1mf.png) | 1135G7 4 Cores/8 Threads@2,42Ghz
![igpu](https://i.imgur.com/HS92HLo.png)| Xe Graphics 1,2GB VRAM @1,4GHz (Not supported)
![audio](https://i.imgur.com/Xpsn2zb.png) | Tiger-Lake Smart Sound I2C/Everest ESSX8336 (Not supported)
![wlan](https://i.imgur.com/9eDLwo9.png) | AX201
![lpddr4](https://i.imgur.com/1VtslzT.png) | 8GB(4x2) LPDDR4@2667Mhz (in-build)
![nvme](https://i.imgur.com/J9Q96yY.png) | 311CD0 NVMe 512GB (TLC PS5013 Controller)
---


### Works:
---
<details>

- Opencore 0.9.3 ✅ 

- Installer Boot ✅ (Installation on: NVMe SSD: 15 minutes; SATA3 SSD: 25 minutes)

- System Boot ✅

- USB Ports ✅ (Now all works).

- VoodooPS2Controller/Keyboard ✅ (Works).
  
- VoodooI2CHID/Touchpad ✅ (Recognize the GXTP7863 sensor weird, works but skips some screen pixels).

- Camera ✅ (works perfectly)

- Battery charging and stats ✅

- Screen ✅ (1080x1920)

 
</details>


### Partially Works:

---
<details>

- Wi-Fi ✅❌ (Maybe will fix with HeliPort)

- Bluetooth ✅❌ (Partially works, if you're using headphones/airbuds, audio might have some cuts).

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

