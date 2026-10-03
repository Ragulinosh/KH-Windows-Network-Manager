# KH Windows Network Manager

**Manage network profiles, diagnose connections and configure physical Windows network adapters.**

KH Windows Network Manager by Kevin Heß is designed for users who frequently switch between networks or work with multiple physical network adapters.

This repository provides documentation and application downloads. The application source code is not published here.

## Download

Visit [Releases](https://github.com/Ragulinosh/KH-Windows-Network-Manager/releases) and expand **Assets** for the version you want to download.

For version **0.9.52 Beta**, download:

`KH-Windows-Network-Manager-v0.9.52-Beta-win-x64.zip`

The automatically generated **Source code** archives contain the repository files, not the Windows application.

## Getting started

1. Download the application ZIP from Releases.
2. Extract all files into a folder.
3. Run `KHWindowsNetworkManager.exe` and approve the administrator prompt.
4. Keep the included README and license files with the application.

The Windows x64 release includes the required .NET runtime. A separate .NET installation is not required for this package.

## Features

- View physical network adapters and their IPv4, DHCP, DNS and gateway settings.
- Save, edit, detect, test and apply network profiles.
- Automatically try saved profiles after a detected new connection when no physical adapter already provides a working, matching profile connection.
- Manage multiple physical adapters and enable or disable them.
- Run adapter-specific connection diagnostics and network discovery.
- Use **Magic Fix** to search progressively for a working configuration, with pause, cancel and restoration of temporary changes.
- Work with Windows proxy settings.
- Switch between English and German interfaces.

## Requirements

- Windows on an x64 system.
- Administrator privileges for network configuration changes.

## Beta status

Version **0.9.52** is a beta release. Hardware validation, particularly with multiple network adapters and rapid cable changes, is still ongoing.

Network changes can interrupt active connections. Temporary profile tests attempt to restore the previous network and proxy configuration. If restoration cannot be confirmed, the affected automatic workflow stops and reports the problem.

Magic Fix searches for unusual private networks can take a long time. A responding gateway alone does not confirm Internet access or the correct subnet mask.

## Reporting issues

Please [open an issue](https://github.com/Ragulinosh/KH-Windows-Network-Manager/issues) and include:

- Application version and Windows version
- Number and type of network adapters involved
- Steps to reproduce the problem
- Expected and actual behavior
- A screenshot if helpful, with confidential network details removed

## License

Free to use under the included **Freeware Binary License**. See `LICENSE-en.txt` and `LICENSE-de.txt` in the download package for the full terms.

Third-party components have their own license terms. See the included `THIRD-PARTY-LICENSES` files.

© 2026 Kevin Heß
