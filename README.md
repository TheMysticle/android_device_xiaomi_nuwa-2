# Xiaomi 13 Pro (nuwa) – Device Tree

![Xiaomi](https://img.shields.io/badge/Xiaomi-13_Pro-blue?style=flat-square)  
**Device tree for Xiaomi 13 Pro (codename: nuwa)**

This repository contains the device configuration for the Xiaomi 13 Pro (*nuwa*), facilitating the building of custom Android ROMs.

---

## 📱 Device Specifications

- **Model:** Xiaomi 13 Pro
- **Codename:** `nuwa`
- **Release Date:** December 2022
- **SoC:** Qualcomm SM8550-AB Snapdragon 8 Gen 2
- **GPU:** Adreno 740
- **Display:** 6.73" LTPO OLED, 1440 x 3200 pixels, 120Hz
- **RAM:** 8GB / 12GB
- **Storage:** 128GB / 256GB / 512GB
- **Rear Cameras:** Triple 50MP setup
- **Front Camera:** 32MP
- **Battery:** 4820mAh, 120W wired charging, 50W wireless charging
- **OS:** Originally shipped with Android 13-based MIUI 14; upgradable to HyperOS based on Android 15

---

## 📂 Repository Structure

```
.
├── AndroidProducts.mk
├── BoardConfig.mk
├── device.mk
├── init/
├── overlay/
├── proprietary-files.txt
├── sepolicy/
└── vendor/
```

- `init/`: Initialization scripts and configurations.
- `overlay/`: AOSP overlays for UI and feature modifications.
- `sepolicy/`: SELinux policy adjustments.
- `proprietary-files.txt`: List of proprietary blobs required for functionality.
- `vendor/`: Vendor-specific configurations.

---

## 🛠️ Building Instructions

1. **Clone the device tree:**

   ```bash
   git clone https://github.com/TheMysticle/device_xiaomi_nuwa-2.git device/xiaomi/nuwa
   ```

2. **Clone the common device tree:**

   ```bash
   git clone https://github.com/TheMysticle/Xiaomi_sm8550-common-new.git device/xiaomi/sm8550-common
   ```

4. **Build the ROM:**

   ```bash
   brunch nuwa
   ```

*Ensure that you have synced the necessary vendor and kernel sources specific to the Xiaomi 13 Pro.*

---

## 📸 Device Images

<p align="center">
  <img src="https://fdn2.gsmarena.com/vv/pics/xiaomi/xiaomi-13-pro-1.jpg" alt="Xiaomi 13 Pro Front View" width="300"/>
  <img src="https://fdn2.gsmarena.com/vv/pics/xiaomi/xiaomi-13-pro-2.jpg" alt="Xiaomi 13 Pro Back View" width="300"/>
</p>

---

## 📜 License

This project is licensed under the [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0).

---

## 📫 Contact

For questions or collaboration:

- **Maintainer:** [TheMysticle](https://github.com/TheMysticle)
- **Telegram:** [@TheMysticle]

---

Happy building! 🚀
