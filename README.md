<div align="center">

# WinOptKP

### Windows tools for checking your PC and managing settings in one place.

Monitor system activity, clean up selected files, troubleshoot network settings, and review Windows tweaks before you apply them.

[**Microsoft Store ↗**](https://apps.microsoft.com/detail/9nb5v71xc9zh?hl=en-US&gl=IN) · [**Latest GitHub release**](https://github.com/kpssisccool/WinOptKP/releases/latest) · [**Report a problem**](https://github.com/kpssisccool/WinOptKP/issues/new)

[![Latest release](https://img.shields.io/github/v/release/kpssisccool/WinOptKP?display_name=tag&sort=semver)](https://github.com/kpssisccool/WinOptKP/releases)
[![License](https://img.shields.io/badge/license-Proprietary-red)](LICENSE)

</div>

---

## About WinOptKP

WinOptKP is a Windows 11 desktop utility that brings several system tools and settings together in one app. You can check hardware and system information, remove selected temporary files, troubleshoot network problems, and manage a range of Windows privacy and performance settings. It also records supported changes, checks their state where possible, and provides a way to undo changes that have a supported revert operation.

Version **1.0.0** moves the application to **WinUI 3** and introduces a redesigned interface, with lower memory use and improved responsiveness compared with the previous versions.

## Features

| Section | What you can do |
|---|---|
| **Dashboard** | View CPU load, RAM use, disk space, and other system information. Scan temporary files, network settings, and telemetry configuration. |
| **Hardware information** | Check details about the processor, graphics hardware, memory, storage, drivers, and Windows installation. |
| **System cleanup** | Remove user and system temporary files, Prefetch data, and selected system log files. Review the commands before running a cleanup. |
| **Network & DNS** | Flush the DNS resolver cache, reset the Winsock catalog, and reinitialize the TCP/IP stack when troubleshooting connection problems. |
| **Privacy & telemetry** | Manage supported Windows telemetry services, including Connected User Experiences and WAP Routing, and disable web queries in Start menu search. |
| **Performance & power** | Make the Ultimate Performance power plan available and adjust selected Windows visual effects. 
| **Change history** | See which supported tweaks have been applied, check their current state, and revert changes when a revert operation is available. |
| **System Restore** | Use the supported Windows System Restore functions before making system changes. |
| **Live console** | Follow command execution and see the output produced by operations running in the app. |

The information and options available can vary with your Windows build, hardware, drivers, and permission level. 
**Features are subject to change in future**

The change log and revert options are useful, but they do not make every operation reversible. In particular, files deleted by System Cleanup cannot be restored through WinOptKP. Read the description for each option and make sure you understand what it changes before proceeding.

## Download and install

WinOptKP is available through the Microsoft Store and as a standalone download from GitHub.

### Microsoft Store

[**Get WinOptKP from Microsoft Store ↗**](https://apps.microsoft.com/detail/9nb5v71xc9zh?hl=en-US&gl=IN)

Install the Store edition from its product page. Microsoft Store handles installation and delivery of Store updates.

### Standalone edition

[**Download the latest release from GitHub ↗**](https://github.com/kpssisccool/WinOptKP/releases/latest)

1. Open the latest release.
2. Download `Setup_WinOptKP.exe` from the release assets.
3. Run the installer and follow the prompts.
4. Open WinOptKP from the Start menu or the shortcut created during installation.

Some operations need administrator permissions. Windows will ask for approval when an operation requires elevation.

## A few things to keep in mind

WinOptKP can change Windows services, network configuration, and other system settings. Take a moment to read each option before using it.

- Create a Windows System Restore point before making significant changes, where System Restore is available.
- The revert option only applies to changes for which WinOptKP has a supported reversal procedure.
- **System Cleanup permanently removes the selected files.** Those files cannot be recovered through WinOptKP's revert function.
- Network reset operations can interrupt your connection and may affect custom network settings.
- Performance and memory settings do not have the same effect on every PC. The result depends on the hardware, Windows configuration, and the workload.

## Updates

For the standalone edition, check [GitHub Releases](https://github.com/kpssisccool/WinOptKP/releases) for new versions, release notes, installers, and checksums. The Microsoft Store edition is updated through Microsoft Store.

## Project links and support

| Resource | Link |
|---|---|
| **Microsoft Store** | [WinOptKP product page](https://apps.microsoft.com/detail/9nb5v71xc9zh?hl=en-US&gl=IN) |
| **GitHub repository** | [kpssisccool/WinOptKP](https://github.com/kpssisccool/WinOptKP) |
| **Latest release** | [Download the latest version](https://github.com/kpssisccool/WinOptKP/releases/latest) |
| **Release history** | [All releases](https://github.com/kpssisccool/WinOptKP/releases) |
| **Bug reports and feature requests** | [Open an issue](https://github.com/kpssisccool/WinOptKP/issues/new) |
| **Privacy policy** | [Read the privacy policy](Privacy-Policy) |
| **License** | [End-User License Agreement](LICENSE) |

When opening an issue, include your WinOptKP version, Windows edition and build, what you were trying to do, and what happened instead. The exact error message is often more useful than a description such as “it did not work.” Screenshots can help too, but check them for personal information before posting.

## Privacy

WinOptKP does not require an account and does not include advertising. System information used for monitoring, diagnostics, and optimization is processed locally on your device. The application does not intentionally send your system telemetry, Registry configuration, optimization history, local logs, or diagnostic information to the developer.

The app may connect to services such as GitHub or Microsoft for releases, downloads, updates, and Store distribution. Those services may process ordinary technical information when you use them, under their own privacy policies. See the [Privacy Policy](Privacy-Policy) for the full explanation.

## About the project

WinOptKP is an independent project designed and developed by **Sai Karthikeya Palaparthi**. It is not affiliated with or endorsed by Microsoft or any other company.

## License

WinOptKP is proprietary software. Use of the application is governed by the [End-User License Agreement](LICENSE). The license does not permit modification, reverse engineering, or redistribution.

Copyright © 2026 Palaparthi Sai Karthikeya. All rights reserved.
