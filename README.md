# Old-Device-Revival 🚀

*An open-source project that gives old devices a new lease on life - an Android system porting solution based on Generic System Image (GSI)*

## 📖 Project Introduction

This project aims to enable older Android devices to run newer Android systems by porting Generic System Image (GSI), improving device performance and security.

**Currently Main Devices**: Huawei DRA-AL00/DUA-AL00

## 🛠️ Features

- ✅ Based on Android GSI

- ✅ Kernel Optimization and Driver Fixes

- ✅ System Performance Tuning

## 📋 Device Support List

| Device Model | Android Base Version | Upgradeable to | Status | Main Issues |

|---------|-----------------|---------|------|---------|

| Huawei DUA-AL00 | Android 8.1.0 | Android 9 GSI | Complete | Auto Brightness, VoLTE |

| Huawei DUA-AL00 | Android 8.1.0 | Android 10 GSI | Complete | Slight UI delay (when just loading the home screen), VoLTE, Hotspot sharing |

| Huawei DUA-AL00 | Android 8.1.0 | Android 11 GSI | Under Testing | GPU Not Working Properly in OpenGL (Skia) |

## 📁 File Description

- `boot.img` - Custom kernel image for Huawei DRA-AL00/DUA-AL00
- `twrp.img` - Twrp recovery image for Huawei DRA-AL00/DUA-AL00
## 🤝 Contribution

Contributions in any form are welcome! You can:

- Report bugs

- Submit feature requests

- Improve documentation

- Submit code fixes

## 📞 Contact Us

- Email: luochenghai2024@gmail.com & luochenghai2022@outlook.com

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Credits & Thanks

This ROM is built on the following open-source projects, and I would like to express my sincere gratitude to them:

* **[Phhusson](https://github.com/phhusson)** - @phhusson

* The system image used in this project is compiled based on this project. Thanks to PHH for his outstanding work in the GSI field.

* **[LineageOS](https://lineageos.org/)** / **[AOSP](https://source.android.com/)**

* Provides the basic source code for the Android system.

* **Complete GSI image:** Please go to [PHH's GSI release page](https://github.com/phhusson/treble_experimentations/releases) to download the corresponding version.

--- **License Notice:** This project follows the open-source licenses of its dependent projects (such as Apache License 2.0, GPL, etc.). Please use it while respecting the original project licenses.
