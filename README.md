# 🛠 OderSo Minecraft Client - Config Manager

A themeable and feature-rich configuration manager for Minecraft Bedrock Edition (UWP).
It helps players manage their `.conf` files easily with a sleek GUI, animated themes, and backup/restore features.

---

## ✨ Features

* 🎨 **Multiple Themes**: Dark, Light, and White themes with animated transitions
* 📁 **OderSo CLient Path Detection**: Automatically finds the config folder
* 🧲 **Drag & Drop Import**: Just drop `.conf` files to add them
* 🔄 **Backups & Restore**: Automatically backup and restore `default.conf`
* ✅ **Default Config Management**: One-click set/reset of default
* 🧱 **Crosshair & Block Overlay Support**: Add PNGs directly
* 🔊 **Audio Config Importing**: Add and manage sounds (MP3/WAV/OGG)
* 💾 **Persistent Settings**: Saves theme and warnings
* 🔒 **Optional Confirmations**: For safe delete & overwrite

---

## 📦 Installation

### 🔹 Download `.exe`

1. Go to the [Releases](https://github.com/Xem7z/OderSo-Config-Manager/releases) page
2. Download the latest `.exe`
3. Run it — it will auto-detect your Minecraft UWP config folder


---

## 📁 Folder Locations

The manager uses this path by default:

```
%localappdata%\Packages\Microsoft.MinecraftUWP_8wekyb3d8bbwe\RoamingState\OderSo\
```

* `Configs/` – stores `.conf` files
* `Images/Crosshair/` – for PNG crosshairs
* `Images/BlockOverlay/` – for overlay images
* `Audio/` – for MP3/WAV/OGG sound config

---

## 💻 Developer Notes

* Built using `tkinter`, `Pillow`, `mutagen`, and `tkinterdnd2`
* Fully standalone GUI
* No external launchers or Minecraft modification required

---

## 📬 Feedback & Support

Currently I don't have any specific own discord server to provide. However, you can ping me in this Discord Server:
**[Discord](https://discord.gg/XN9uPbQ3Bm)**

---

## ❗ License

This project is shared for educational use. You may not reuse, modify, or redistribute without permission.
