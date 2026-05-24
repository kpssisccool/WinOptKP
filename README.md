# WinOptKP
**WinOptKP** is an advanced Windows optimization tool that moves away from opaque tweaks. It features a modern UI allowing users to audit commands before execution, clear system junk, disable telemetry, tune MMAgent memory settings, and safely revert changes using a built-in system log and live console.

---

## 📸 Interface Overview
<img width="1920" height="1030" alt="image" src="https://github.com/user-attachments/assets/bdf70c54-d60c-468b-af87-4aaa770a93a5" />


---

## 🚀 Features

WinOptKP is divided into dedicated modules to give you precise control over your operating system:

### 📊 Dashboard
* **Real-Time Monitoring:** Live tracking of CPU Load, RAM Usage, and Disk Space.
* **System Scan:** Analyze temporary clutter, network settings, and telemetry configurations before applying any changes.

### 🗑️ System Cleanup
* **Granular Cache Sweeping:** Clear User Temp Files, System Temp Files, Prefetch Cache, and System Log Files.
* **Command Visibility:** See the exact Windows commands (e.g., `rmdir /s /q "%TEMP%"`) that will be executed before you click apply.

### 🌐 Network & DNS
* **Connectivity Fixes:** Flush the local DNS resolver cache, reset the Winsock catalog, and reinitialize the TCP/IP stack to restore network stability.

### 🛡️ Privacy & Telemetry
* **Telemetry Shields:** Disable the Windows Telemetry Service (Connected User Experiences) and WAP Routing Service.
* **Start Menu Debloat:** Turn off integrated web queries in the Windows Start Menu for a faster, local-only search experience.

### ⚡ Performance & Power Tweaks
* **Basic Performance:** Unlock the hidden Windows Ultimate Performance power plan and optimize visual animations for UI speed.
* **Advanced Power-User Settings:**
  * **MMAgent Tuning:** Direct control over the Windows kernel Memory Manager Agent (toggle Memory Compression, Page Combining, Pre-launching, etc.).
  * **CPU Priority Separation:** Adjust thread scheduling focus to prioritize the foreground active application—ideal for heavy workloads or maintaining stable frame rates.

### ⏪ Revert Changes & Safety
* **Applied Tweaks Log:** WinOptKP keeps a record of the optimizations you've applied.
* **Revert System Changes:** Easily undo system modifications and return them to standard Windows defaults. *(Note: File deletions from System Cleanup cannot be reverted).*

### >_ Live Console
* **Live Execution Terminal:** Monitor live system output and execution commands right inside the app, running with elevated administrative permissions.

**Disclaimer of Feature Continuity: The developer reserves the right to modify, add, or deprecate any features, system tweaks, or UI components described herein. The current feature list reflects the application state at the time of documentation and is not a binding commitment for future functionality.**
---

## 🛠️ Installation & Usage

1. **Download** the latest release installer from the (https://github.com/kpssisccool/WinOptKP/releases) page.
2. **Run as Administrator:** WinOptKP requires elevated privileges to modify system services, network stacks, and registry keys. The app will verify permissions on launch.
3. **Navigate & Apply:** Select a category from the sidebar, review the tweaks, and click the apply button for your selected fixes.


**Update Cycle: As a native desktop application, WinOptKP requires manual verification for new builds. To ensure you are running the most optimized version, please check the Releases section on GitHub weekly. Note that an integrated automatic update feature is currently in active development and will be included in a future release to streamline this process.**

---

## ⚖️ Legal & License

**DO NOT INSTALL THIS APPLICATION WITHOUT READING THE LICENSE**

**License:** The full legal license and terms of use can be viewed during the installation process, directly within this GitHub repository (see the `LICENSE` file), or at any time via the **Settings** menu within the application.

---
**Developer:** Sai Karthikeya Palaparthi  
