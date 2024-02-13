# [WIP-WONT BOOT] Huawei Matebook D14 (2021) Hackintosh Sonoma with OpenCore

![img](https://i.imgur.com/Eur6M5c.png)

⚠️**WARNING**: For install and test it, USE an USB 2.0 HUB beside from USB Type-C charging port, 3.1 USB ports doesn't work ⚠️

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

- Opencore 0.9.3 ✅ (OC starts, but MacOS Sonoma Image won't boot).

- Installer Boot ❌ (IDK for the moment.
NVMe 35 minutes; SSD 45/50 minutes, I guess).

- System Boot ❌ (Not for now).

- Camera ✅ (works perfectly 🙃)

- Battery charging and stats ✅ (It's recognize)

- Screen ✅ (1080x1920)

- Wi-Fi ✅❌ (Maybe with HeliPort)

- VoodooPS2Controller/Keyboard ✅ (Works).
  
- VoodooI2CHID/Touchpad ✅ (Recognize the GXTP7863 sensor weird, works but skips some screen pixels).

 
</details>


### Partially Works:

---
<details>
 
- USB Ports ✅❌ (2.0 and Type-C ports works perfect; 3.1 ports doesn't work for now).
- 
- VoodooPS2Controller ✅❌ (Works, but touchpad is broken, after boot seems work but stops inmediatelly).

- Bluetooth ❌ (Almost any Intel wireless cards with Bluetooth are broken on Ventura/Sonoma).

</details>


### Not works:
---

<details>

- Audio Card ❌ (It's recognized but isn't enabled)

- Microphone ❌ (It's recognized but isn't enabled)

- HDMI ❌ (Doesn't work without 3D Acceleration)

- Screen Backlit ❌ (Doesn't work without 3D Acceleration)

- Fingerprint Scanner ❌ (Don't exist some Goodix kext for MacOS)

</details>

