# 🛠️ LAUNCHER-TOOLS

A collection of utility tools designed for Minecraft Android launchers that are missing specific built-in features. 

If your favorite launcher doesn't have a feature you need, you'll likely find a tool for it here.

---

## 📸 Screenshots
Screenshot_20260628-114535.jpg

## 📦 Available Tools

### 1. Modpack Exporter (Android)
**Status:** ✅ Available

An Android application built with Jetpack Compose and Material You that allows you to export your Minecraft launcher instances into standard **Modrinth (`.mrpack`)** and **CurseForge (`.zip`)** modpack formats.

#### ❓ Why does this exist?
Some popular Android launchers (like **Zalith Launcher 1**) do not have a built-in "Export Modpack" feature. This tool bridges that gap, allowing you to easily package your mods, configs, and resource packs to share with others or import into desktop launchers like Prism, ATLauncher, or Modrinth App.

#### ✨ Features
- **Dual Format Support:** Export to both Modrinth (`.mrpack`) and CurseForge (`.zip`) formats.
- **Interactive File Tree:** Easily browse your instance and toggle exactly which files and folders you want to include.
- **Smart Filtering:** Automatically skips unnecessary files like logs, cache, launcher internals (`.fabric`, `ZalithLauncher`), and unselects saves by default.
- **Built-in Code Editor:** Edit `.json`, `.toml`, `.txt`, and other config files directly inside the app using the **Sora Editor** with syntax highlighting and dark mode support.
- **Open With:** Open `.zip`, `.jar`, or image files using your favorite external Android apps.
- **Auto-Detection:** Automatically detects your Minecraft version and Modloader (Fabric, Forge, Quilt).
- **Material You Design:** Beautiful, dynamic UI that adapts to your system's wallpaper colors.
- **Fullscreen Mode:** Expand the file browser to fullscreen for easier navigation on large modpacks.

#### 📱 Supported Launchers
Works with any launcher that uses a standard `.minecraft` directory structure, including but not limited to:
- Zalith Launcher (v1 & v2)
- PojavLauncher
- Fold Craft Launcher
- HMCL-PE

#### 🚀 How to Use
1. Download the latest APK from the [Releases](https://github.com/chappcG/LAUNCHER-TOOLS/releases) page.
2. Open the app and tap **"Select Instance Folder"**.
3. Navigate to your launcher's `.minecraft` folder (usually in `Android/data/[launcher.package.name]/files/.minecraft`).
4. Wait for the file tree to analyze your instance.
5. Choose your export format (Modrinth or CurseForge).
6. (Optional) Expand **Advanced Options** to add a description.
7. Tap the file tree to uncheck anything you don't want to include (like saves or shader packs).
8. Tap **Export** and save the file to your desired location!

---

## ️ Tech Stack
- **Language:** Kotlin
- **UI Framework:** Jetpack Compose
- **Design:** Material Design 3 (Material You)
- **Code Editor:** [Sora Editor](https://github.com/Rosemoe/sora-editor)

---

## 🤝 Contributing
Have an idea for a new tool or want to improve an existing one? 
1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a Pull Request.

---

## 📄 License
This project is open-source and available under the [MIT License](LICENSE).

---

*Disclaimer: This project is not affiliated with Mojang Studios, Microsoft, Modrinth, or CurseForge.*