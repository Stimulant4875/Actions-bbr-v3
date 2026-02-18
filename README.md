# ✨ BBR Management Script ✨

A simple, efficient, and feature-rich **BBR management script** designed for Debian/Ubuntu users.

Whether you want to install the latest **BBR v3 kernel** with one click or flexibly switch between different network acceleration schemes, this script makes it effortless.

> **We are committed to providing an elegant interface and smooth experience — making kernel management no longer a headache.**

---

## 🎯 Target Users & Supported Environment

Before running the script, please ensure your device meets the following requirements:

| Item                        | Requirement                                                   |
| :-------------------------- | :------------------------------------------------------------ |
| **Supported Architectures** | `x86_64` / `aarch64`                                          |
| **Supported Systems**       | Debian 10+ / Ubuntu 18.04+                                    |
| **Target Devices**          | **Cloud Servers (VPS/Cloud Server)** or **Dedicated Servers** |
| **Boot Mode**               | Standard `GRUB` bootloader                                    |

> ⚠️ **Important Notice**
> This script is **NOT compatible** with most single-board computers (SBC), such as **Raspberry Pi**, **NanoPi**, etc.
> These devices typically use non-GRUB bootloaders (e.g., U-Boot), which will cause the script to fail.

---

## 🌟 Features

👑 **One-click installation of BBR v3 kernel**
🍰 **Switch acceleration modes (BBR+FQ, BBR+CAKE, etc.)**
⚙️ **Enable/Disable BBR acceleration**
🗑️ **Uninstall unwanted kernel versions**
👀 **View current TCP congestion control & queue discipline in real time**
🎨 **Enhanced and visually friendly output interface**

---

## 🚀 How to Use

### 1️⃣ One-Click Run

```bash
bash <(curl -l -s https://raw.githubusercontent.com/byJoey/Actions-bbr-v3/refs/heads/main/install.sh)
```

---

## 🌟 Interactive Interface

Each time you run the script, you will enter a lively and practical interactive menu:

```bash
╭( ･ㅂ･)و ✧ Please choose an option:
  1. 🛠️  Install BBR v3
  2. 🔍 Check if BBR v3 is active
  3. ⚡ Enable BBR + FQ
  4. ⚡ Enable BBR + FQ_PIE
  5. ⚡ Enable BBR + CAKE
  6. 🔧 Enable or Disable BBR
  7. 🗑️  Uninstall
```

> **Tip:** If you select the wrong option, no worries — the script will guide you accordingly.

---

## 🌟 FAQ

**Q: Why did the download fail?**
A: The GitHub link may have expired. Feel free to report the issue in the feedback group.

**Q: I'm not a BBR expert. Which acceleration mode should I choose?**
A: No worries! **BBR + FQ** is the most common and recommended option for most scenarios.

**Q: What if I accidentally break my system?**
A: Stay calm! Always back up your kernel beforehand, or visit [Joey's Blog](https://joeyblog.net) for recovery tutorials.

---

## 🌈 Author

**Joey**
📖 Blog: [JoeyBlog](https://joeyblog.net)
💬 Telegram Group: [Telegram Feedback Group](https://t.me/+ft-zI76oovgwNmRh)

---

## ❤️ License

You are welcome to use, modify, and distribute this script.
If you find it helpful, please consider giving it a ⭐ Star!

> 💡 **Disclaimer:**
> This script is developed with a passion for Linux. While every effort has been made to ensure safety and stability, you assume all risks associated with its usage.

---

## 🌟 Special Thanks

Special thanks to the
[Naochen2799/Latest-Kernel-BBR3](https://github.com/Naochen2799/Latest-Kernel-BBR3)
project for technical support and inspiration.
.
