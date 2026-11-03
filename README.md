# Auger — Dedicated Server Manager for 7 Days to Die

> **Official Prebuilt Releases & Distribution Repository**  
> Maintained by [RBND](https://github.com/RBND) | Current Release: **v2.1.6**

Auger is a modern, high-performance, native desktop application and CLI dedicated server manager for **7 Days to Die** on Windows and Linux.

---

## 📥 Direct Downloads (v2.1.6)

| Platform | Download Link | Description | Size |
| :--- | :--- | :--- | :--- |
| **Windows x86_64** | [**Auger.exe**](https://github.com/RBND/Auger-Releases/releases/download/v2.1.6/Auger.exe) | Native standalone Windows desktop application | ~9.5 MB |
| **Linux x86_64** | [**Auger-linux-x86_64**](https://github.com/RBND/Auger-Releases/releases/download/v2.1.6/Auger-linux-x86_64) | Standalone Linux ELF binary (glibc 2.28+) | ~20 MB |
| **Linux Archive** | [**Auger-linux-x86_64.tar.gz**](https://github.com/RBND/Auger-Releases/releases/download/v2.1.6/Auger-linux-x86_64.tar.gz) | Compressed tarball | ~7.5 MB |

All releases and changelogs are available on the [**Releases Page**](https://github.com/RBND/Auger-Releases/releases).

---

## 🚀 Key Features

- **1-Click 7DTD Dedicated Server Installer & Branch Selector**: Install or switch between Stable, Latest Experimental, or specific legacy alphas via SteamCMD without typing command-line arguments.
- **Global Mod Library & NTFS Junctions**: Canonical mod storage in %LOCALAPPDATA%\Auger\Mods_Library (~/.local/share/auger/mods_library) linked into <server_dir>/Mods via NTFS Junctions / symlinks without administrative elevation.
- **Nexus Mods Integration & 
xm:// Protocol**: Browse Nexus Mods inside the app, enjoy 1-click downloads for Nexus Premium, and seamless browser handoff for Free users.
- **Universal Archive Importer**: Safe extraction of .zip, pure-Rust .7z, and .rar mod packs with recursive mod root detection.
- **EAC & Crossplay Conflict Checker**: Automatic detection of XML-only, client+server assets, and Harmony C# DLL mods, warning when active DLL mods require EAC to be disabled.
- **Client Mod Packager**: 1-click **Bundle Client Mods (.zip)** exports client-required mod assets and XML for easy distribution to server players.
- **Live Telnet RCON & Player Manager**: Real-time connected player list with 1-click kick, ban, and permission assignment, plus safe saveworld shutdown controls that prevent save corruption.
- **Custom Map & World Importer**: 1-click custom world imports from .zip archives or local single-player GeneratedWorlds.
- **Automatic Self-Updater**: In-app 1-click updates with atomic binary replacement.

---

## 🛠️ Getting Started

### Windows
1. Download [Auger.exe](https://github.com/RBND/Auger-Releases/releases/download/v2.1.6/Auger.exe).
2. Place it in any folder and run it. Auger is completely portable.
3. Follow the 3-step First-Run Wizard to configure your server folder and start hosting.

### Linux
`ash
# Download and make executable
curl -L -o Auger https://github.com/RBND/Auger-Releases/releases/download/v2.1.6/Auger-linux-x86_64
chmod +x Auger

# Launch GUI desktop app (or auto-install desktop shortcut)
./Auger --install-desktop

# Or run headlessly via CLI
./Auger status
./Auger update
./Auger start
`

---

## 💬 Issues & Feedback
Please report any issues or feature requests on the [**GitHub Issues**](https://github.com/RBND/Auger-Releases/issues) tab.