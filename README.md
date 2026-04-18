# Axiom God Combo Launcher

One-click mod installer for Crimson Desert / R5.

## Features

- **4 God Mode Presets**: Battle, Farming, Speed, True God Mode
- **One Click Install** — automatically copies mod files to game directory
- **Uninstall All** — cleanly removes all mods
- **Launch Game** — starts R5.exe or CrimsonDesert.exe directly
- **EN / 中文** language toggle
- Custom borderless UI with DirectX 11 + Dear ImGui

## Screenshot

<img width="753" height="771" alt="image" src="https://github.com/user-attachments/assets/630ff259-bbc9-40e5-ba71-d9db56fb9bf5" />


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
