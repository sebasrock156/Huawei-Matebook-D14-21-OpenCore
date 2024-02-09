# Huawei Matebook D14 (2021) Hackintosh BigSur (11.5.2 - 11.6.3) with OpenCore

![img](https://i.imgur.com/31RLUxv.png)

⚠️**WARNING**: For install it, USE an USB 2.0 HUB beside from USB Type-C charging port, 3.0 USB ports doesn't work during installation ⚠️

---

Hardware | Model
--- |:--:
![processor](https://i.imgur.com/BzXF1mf.png) | Intel Core i5 1135G7
![igpu](https://i.imgur.com/HS92HLo.png)| Intel Xe Graphics 1GB VRAM @1,4GHz (Not supported)
![audio](https://i.imgur.com/Xpsn2zb.png) | TigerLake Smart Sound I2C/Everest ES8316(?) (Not supported)
![wlan](https://i.imgur.com/9eDLwo9.png) | Intel 6 Wi-Fi/Bluetooth AX201 (Only Wi-Fi might work)
![lpddr4](https://i.imgur.com/1VtslzT.png) | Samsung 4GB(x2) @2667Mhz (in-build)
![nvme](https://i.imgur.com/J9Q96yY.png) | Phison 311CD0 NVMe 512GB (TLC PS5013 Controller)
---

### Works:
---
<details>

- Opencore 0.9.4 ✅ 

- Installer Boot ✅ (installation is a less of 25 minutes with NVMe)

- System Boot ✅

- Camera ✅

- Battery charging and stats ✅

- USB Devices ✅ (2.0, 3.0/3.1, but no while installing)

- Screen ✅ (1080x1920)

- Wi-Fi ✅ (altrough is some slow to connect)

 
</details>


### Partially Works:

---
<details>

- VoodooPS2Controller ✅❌ (Works, but touchpad is broken).

- Bluetooth ✅❌ (AirportItlwm makes that works partially).

</details>


### Not works:
---

<details>
 
 
- Touchpad ❌ (MacOS doesn't recognize the Huawei sensors).

- Audio Card ❌ (Isn't recognized, I will to spoofing)

- Microphone ❌ (Isn't recognized, I will to spoofing)

- HDMI ❌ (Doesn't work without 3D Acceleration)

- Screen Backlit ❌ (Doesn't work without 3D Acceleration)

- Fingerprint Scanner ❌ (Don't exist some Goodix kext for MacOS)

</details>

