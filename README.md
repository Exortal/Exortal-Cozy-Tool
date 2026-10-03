# Exortal Cozy Tool

**A calmer way to manage your EA SPORTS FC 27 LITE setup.**

Exortal Cozy Tool is a lightweight, unofficial Windows utility designed to help users manage custom files, mods, and settings for their legally owned copies of EA SPORTS FC 27 LITE. 

> ⚠️ **Disclaimer:** This tool is purely a file manager and launcher utility. It **does not** contain, distribute, or promote pirated content, cracked executables, copyrighted game assets, or DRM-bypass software. You must own a legitimate copy of the game via Steam or the EA App to use this software. This project is not affiliated with, maintained, authorized, endorsed, or sponsored by Electronic Arts Inc. or Valve Corporation.

## What it does

- **Safe Modding:** Automates the installation of user-provided custom ZIP packages into your chosen game directory, creating automatic backups of your original files before any modifications are made.
- **Customization:** Manages your local tool preferences, UI language, and naming configurations.
- **Squad Management:** Simplifies the application of user-provided custom squad files or official online squad updates.
- **Official Integration:** Securely triggers the official Steam or EA App verification flows and launches your legally owned game directly through the official clients.

*Note: The app does not include any FC 27 LITE game files, assets, or modified executables. You are responsible for providing your own legal game installation and custom patch files.*

## Safety and Permissions

The application verifies your selected directories and ZIP file structures before making any changes. If you are applying custom packages to a game installed in `Program Files`, Windows may prompt you for administrator approval to modify the folder. Under normal circumstances, the app does not require administrator rights.

**Privacy Note:** Crash diagnostics are saved locally under `%LOCALAPPDATA%\Exortal Cozy Tool\crash.log`. If you choose to share this log for troubleshooting, please review it first, as it may contain local file paths from your PC.

## Download

Download the latest Windows x64 build from [Releases](../../releases). 

*Builds are currently unsigned, meaning Windows SmartScreen may show an "unknown publisher" warning. This is normal for open-source indie tools.*

## Build from Source

**Requirements:** Windows x64 and Go 1.21 or newer.

Run `build.bat` from the project folder. See `BUILDING.txt` for detailed build instructions and diagnostic flags.

## Credits and License

See `LICENSE` for this project’s open-source license, and `FIFASquadFileDownloader_LICENSE.txt` for the included third-party license.
