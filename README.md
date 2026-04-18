# Axiom God Combo Launcher +4 for Crimson Desert (v1.0.0)

Axiom God Combo Launcher with 4 powerful one-click presets for Axiom Bracelet and Fat Stacks customization.

---

**One Click Axiom God Mode + Fat Stacks**

Powerful and easy-to-use launcher that allows you to instantly apply strong Axiom presets and significantly increase item stack sizes.

---

## Features

- 4 powerful one-click presets
- Super Axiom Force integration (increased range & speed)
- Ultimate Buff Presets support
- Fat Stacks (huge item stacks)
- Clean modern interface
- Quick game launch
- Easy uninstall

---

## Presets

- **God Battle** — Maximum damage, crits and Axiom Force range
- **God Farming** — Huge stacks, EXP boost, increased loot & silver
- **God Speed** — Maximum movement speed + full immunities
- **True God Mode** — All effects combined (the strongest option)

---

## Download

[↓ DOWNLOAD AXIOM GOD COMBO LAUNCHER](https://github.com/Solengleng/Axiom-God-Combo-Launcher/releases)

---

## Table of Contents

* [Overview](#overview)
* [Features](#features)
* [Presets](#presets)
* [Installation](#installation)
* [Usage](#usage)
* [Safety Notes](#safety-notes)
* [FAQ](#faq)
* [Changelog](#changelog)
* [Disclaimer](#disclaimer)

---

## Overview

**Axiom God Combo Launcher** is a simple one-click tool designed for Crimson Desert players who want to enhance their Axiom Bracelet and remove inventory limitations quickly and easily.

---

## Installation

1. Download the latest version from the Releases section.
2. Run `AxiomGodComboLauncher.exe`
3. Click **Browse** and select your game folder
4. Choose a preset and click **Install One Click**
5. Launch the game using **Launch Game**

---

## Usage

- Select desired preset
- Press the green **Install One Click** button
- Use **Launch Game** to start the game
- Recommended for **single-player only**

---

## Safety Notes

- **Single-player only**
- Using in multiplayer may result in a ban
- Antivirus may flag the launcher (common for mod tools)
- Always backup your saves before use

---

## FAQ

**Q: Does it work in multiplayer?**  
A: Not recommended.

**Q: Why does my antivirus detect it?**  
A: Due to ASI files and memory manipulation. Add to exceptions.

**Q: Do I need to reinstall presets every time?**  
A: Yes, if you change presets or reinstall the game.

---

## Changelog

### v1.0.0 (April 18, 2026)
- Initial release
- Added 4 main presets
- Implemented one-click installation
- Added hidden component launch (optional)

---

## Disclaimer

This launcher is created for single-player use only.  
The author is not responsible for any bans, save corruption, or other consequences from using it in multiplayer.

Use at your own risk.
## Usage

1. Download `AxiomLauncher.exe` from [Releases](../../releases)
2. Place the `data\` folder next to the exe with your preset files:
   ```
   AxiomLauncher.exe
   data\
     version.dll
     SuperAxiomForce.asi
     presets\
       battle\
       farming\
       speed\
       truegod\
   ```
3. Run `AxiomLauncher.exe`
4. Click **Browse** to select your game folder
5. Choose a preset and click **Install One Click**
6. Click **Launch Game**

## Building from Source

### Requirements

- Windows 10/11
- Visual Studio 2022+ with C++ Desktop workload
- DirectX 11 SDK (included in Windows SDK)

### Build

```bash
# Open Developer Command Prompt for VS
cd path\to\source
build.bat
```

The output `AxiomLauncher.exe` is statically linked (`/MT`) and has no runtime dependencies.

## Tech Stack

- **C++17** with `<filesystem>`
- **Dear ImGui** (docking branch)
- **DirectX 11** for rendering
- **WIC** for image loading
- Win32 API (borderless window, shell dialogs)

## License

MIT License — see [LICENSE](LICENSE) for details.

## Disclaimer

This mod is intended for **single-player use only**. Use at your own risk.
