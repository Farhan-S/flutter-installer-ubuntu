# 🚀 Flutter Installer Script for Ubuntu

Easily install Flutter SDK on Ubuntu (20.04, 22.04 and newer) with this automated shell script. It sets up all required dependencies, configures the environment path, and runs `flutter doctor` for final setup. Ideal for developers who want a quick and hassle-free Flutter setup on Linux.

---

## 🔍 Why Use This Script?

Manual Flutter installation on Ubuntu can be time-consuming and error-prone. This script:

- Installs all necessary dependencies for Flutter
- Downloads and extracts Flutter SDK to `/opt/flutter`
- Adds Flutter to your shell path (`bash` or `zsh`)
- Automatically accepts Android licenses
- Helps you get started in minutes!

---

## 📦 Features

- ✅ One-command setup  
- ✅ Compatible with Ubuntu 20.04 and 22.04+  
- ✅ Supports both Bash and Zsh  
- ✅ No version conflicts  
- ✅ Uses latest stable Flutter SDK  
- ✅ Safe to re-run without breaking setup  

---

## 💻 System Requirements

- Ubuntu Linux (20.04 LTS or newer)
- Admin (sudo) privileges
- Internet connection

---

## 📥 Installation Instructions

### 1. Clone this repository

```bash
git clone https://github.com/your-username/flutter-installer-ubuntu.git
cd flutter-installer-ubuntu
````

### 2. Make the script executable

```bash
chmod +x install_flutter.sh
```

### 3. Run the installer

```bash
./install_flutter.sh
```

---

## 🔧 What the Script Does

1. Updates and upgrades your system.
2. Installs required packages: `curl`, `git`, `unzip`, `xz-utils`, `libglu1-mesa`, etc.
3. Installs additional required libraries for 64-bit systems.
4. Downloads the latest Flutter SDK from the official site.
5. Extracts the SDK to `/opt/flutter`.
6. Detects your current shell (`bash` or `zsh`) and updates the correct config file (`~/.bash_profile` or `~/.zshenv`) to add Flutter to your PATH.
7. Runs `flutter doctor` and accepts Android SDK licenses.

---

## 🧪 Verify Installation

Open a new terminal or run:

```bash
source ~/.bash_profile   # for bash users
source ~/.zshenv         # for zsh users
```

Then check the Flutter version:

```bash
flutter --version
```

---

## 📸 Screenshot (Optional)

> *(Insert a screenshot of the terminal showing successful installation or `flutter doctor` output here)*

---

## ⚠️ Notes

* This script installs Flutter in `/opt/flutter`, which is a system-wide location.
* You can customize the installation directory by modifying the `INSTALL_DIR` variable in the script.
* If you're using fish shell or other custom shells, you'll need to manually add `/opt/flutter/bin` to your PATH.

---

## 📚 Related Resources

* [Official Flutter Installation Guide (Linux)](https://docs.flutter.dev/get-started/install/linux)
* [Flutter GitHub Repo](https://github.com/flutter/flutter)
* [Android Studio Download](https://developer.android.com/studio)

---

## 📝 License

This project is licensed under the [MIT License](LICENSE).

---

## 👨‍💻 Author

Made with ❤️ by Farhan Sadik (https://github.com/farhan-s)

---

## 💡 Keywords (for SEO)

`flutter install ubuntu`, `install flutter on linux`, `flutter setup shell script`, `automated flutter installer ubuntu`, `how to install flutter sdk ubuntu 22.04`, `flutter bash setup`, `flutter zsh path`, `flutter linux developer setup`

---

## 🌍 Contribution

Feel free to open an issue or pull request if you have suggestions, improvements, or bug fixes. Contributions are welcome!


```
