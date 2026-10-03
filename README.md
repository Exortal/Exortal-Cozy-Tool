# Exortal Cozy Tool

![Exortal Cozy Tool logo](icon-preview-256.png)

**A calmer way to manage your FC 27 Lite setup.**

Exortal Cozy Tool is an unofficial Windows utility for managing selected FC 27 Lite files and settings. It is not affiliated with or endorsed by EA or Valve.

## What it does

- Installs a ZIP package into the game folder you choose and backs up files before replacing them.
- Manages the tool’s name and language preferences.
- Helps install squad updates from a local file or the online option.
- Opens the Steam or EA verification flow and can launch the game afterward.

The app does not include FC 27 game files. You need your own game installation and update packages.

## Safety and permissions

The app checks the selected folder and ZIP paths before installing. For a matching FC 27 patch inside Program Files, Windows may ask for administrator approval when the folder requires it. The app does not require administrator rights for normal use.

Crash diagnostics are saved under `%LOCALAPPDATA%\Exortal Cozy Tool\crash.log`. Check the log before sharing it; it may include file paths from your PC.

## Download

Download the latest Windows x64 build from [Releases](../../releases). Builds are currently unsigned, so Windows may show an unknown-publisher warning.

## Build from source

Requirements: Windows x64 and Go 1.21 or newer.

Run `build.bat` from the project folder. See `BUILDING.txt` for build and diagnostic details.

## Credits and license

See `LICENSE` for this project’s license and `FIFASquadFileDownloader_LICENSE.txt` for the included third-party license.
