# Simpltask

[![Latest Release](https://img.shields.io/github/v/release/AdamAnomatik/Simpltask-Releases?label=Latest%20Release)](https://github.com/AdamAnomatik/Simpltask-Releases/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/AdamAnomatik/Simpltask-Releases/total?label=Downloads)](https://github.com/AdamAnomatik/Simpltask-Releases/releases)
[![Windows](https://img.shields.io/badge/Platform-Windows-0078D4)](https://github.com/AdamAnomatik/Simpltask-Releases/releases/latest)

[Русский](README.md) · **English**

<p align="center">
  <img src="simpltask-preview.png" alt="Simpltask preview" width="1000">
</p>

**Simpltask** is a compact Windows utility that provides quick access to frequently used files and folders directly from the taskbar.

## Features

- Quick access to files and folders from a compact Launcher.
- Add and manage items through Simpltask Manager.
- Drag and drop files and folders.
- Reorder items.
- Configurable global hotkey.
- Light, dark, and system themes.
- Adjustable transparency for Launcher, Manager, and Settings.
- Interface language selection: **System**, **Русский**, or **English**.
- Multi-monitor support.
- Your item list and preferences are preserved between updates.

## Download

The latest stable version is available in **Releases**.

➡️ **[Download the latest version of Simpltask](https://github.com/AdamAnomatik/Simpltask-Releases/releases/latest)**

### Files

- `Simpltask-Setup-x.y.z.exe` — application installer.
- `Simpltask-Setup-x.y.z.sha256.txt` — SHA-256 checksum for verifying the downloaded file.

## System requirements

- 64-bit Windows 11.
- The application only needs to be pinned to the taskbar once after installation.

## Installation

1. Download the latest `Simpltask-Setup-x.y.z.exe`.
2. Run the installer.
3. After the first launch, pin Simpltask to the taskbar.
4. Click the pinned icon to open the Launcher.

## Updating

Run the new installer over the previous version.

Your item list and user settings are preserved.

## Data location

User data is stored locally:

```text
%LOCALAPPDATA%\Simpltask
```

Simpltask does not require an account and does not upload your file or folder list to a remote server.

## Verify SHA-256

You can verify the installer checksum in PowerShell:

```powershell
Get-FileHash .\Simpltask-Setup-x.y.z.exe -Algorithm SHA256
```

The result must match the value published in `Simpltask-Setup-x.y.z.sha256.txt`.

## Report an issue

Found a bug or have a suggestion?

➡️ **[Open an issue](https://github.com/AdamAnomatik/Simpltask-Releases/issues/new/choose)**

Please include:

- your Simpltask version;
- your Windows version;
- steps to reproduce the issue;
- a screenshot when it helps explain the problem.

## License and source code

Simpltask is distributed as closed-source software.

This repository is used to publish installers, release notes, and issue reports.
