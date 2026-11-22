<img width="1167" height="360" alt="hyadeOS" src="https://github.com/user-attachments/assets/75bb4aad-f059-44b1-9c6e-77df29639fc2" />

# hyadeOS

**A clean, fast, smooth web-based desktop experience.**
Its own design, accounts, an app store and safe automatic updates. Open source, no ads, no data collected.

<p align="center">
  <img width="900" alt="The hyadeOS desktop" src="https://github.com/user-attachments/assets/ec2f5a05-f8bb-4988-a624-ee1bfa3075ba" />
  <br><sub><i>The hyadeOS desktop: Start bar, snapped windows and a custom wallpaper.</i></sub>
</p>

---

## Contents

1. [Install hyadeOS](#install-hyadeos)
2. [What you get](#what-you-get)
3. [Updates](#updates)
4. [Versions and channels](#versions-and-channels)
5. [Run from source (developers)](#run-from-source-developers)
6. [Build apps for hyadeOS](#build-apps-for-hyadeos)
7. [Organizations and custom builds](#organizations-and-custom-builds)
8. [License and credits](#license-and-credits)

---

## Install hyadeOS

You can install the **whole operating system** with the official installer, published in the stable releases:

### 👉 [github.com/hyadeOSS/stable/releases](https://github.com/hyadeOSS/stable/releases)

1. Open the releases page above.
2. Download the installer (`.exe`) from the latest release.
3. Run it and follow the guided setup.
4. Launch **hyadeOS** from the Start menu or the desktop shortcut.

The installer needs nothing else: no Git, no Node.js. Your data lives in your Windows user folder, so updates and reinstalls never touch it.

<p align="center">
  <img width="800" alt="The stable releases page" src="https://github.com/user-attachments/assets/60469853-f8c1-40f0-a9ce-2aef7c0ff260" />
  <br><sub><i>Step 1-2: the stable releases page, where you download the installer.</i></sub>
</p>

<p align="center">
  <img width="800" alt="The hyadeOS installer" src="https://github.com/user-attachments/assets/fc87fa32-b464-4728-8aa3-b2ffea02cef8" />
  <br><sub><i>Step 3: the guided installer.</i></sub>
</p>


---

## What you get

- **A real desktop.** Start menu, windows that snap, virtual desktops, and the Windows shortcuts working inside hyadeOS (Win, Win+L, Win+D, Win+arrows, Win+V, Win+Shift+S...).
- **Global search** (Win+S): apps, your files, settings and quick calculations.
- **Widgets** (Win+W): clock, weather, today's events, notes and what is playing.
- **Live wallpapers** (MP4, WebM, GIF) and a dynamic island for music, timers and updates.
- **Accounts.** Several users with their own password and files, a guest account, parental controls and a personal backup.
- **App store.** Apps from GitHub, with the permissions they ask for shown before you install, and optional automatic updates.
- **Built-in apps.** Calculator, Calendar, Explorer, Music, Notes, Pictures, Video player, Terminal, Settings, Store and Help. The Browser app supports multiple tabs, each in its own isolated webview.
- **Private by default.** The optional anonymous usage count sends only the version and update channel, once a day, and only if you turn it on.

<p align="center">
  <img width="800" alt="Start menu and global search" src="https://github.com/user-attachments/assets/57ae6529-911e-43f7-be37-82ea4e40a62b" />
  <br><sub><i>Start menu and global search (Win+S): apps, files, settings and quick calculations.</i></sub>
</p>

<p align="center">
  <img width="260" alt="Widgets panel" src="https://github.com/user-attachments/assets/fa08eb72-1462-45b8-aa8b-909ff934ccf7" />
  <br><sub><i>Widgets (Win+W): clock, weather, today's events and notes.</i></sub>
</p>

<p align="center">
  <img width="800" alt="Snapped windows" src="https://github.com/user-attachments/assets/84ac8c0f-91c3-4621-82c5-10c4ccef468d" />
  <br><sub><i>Windows that snap side by side, to work with several apps at once.</i></sub>
</p>

<p align="center">
  <img width="800" alt="App store" src="https://github.com/user-attachments/assets/1bb09647-e988-49d5-8111-bb84e792b015" />
  <br><sub><i>The app store: apps from GitHub, with their permissions shown before you install.</i></sub>
</p>

<p align="center">
  <img width="800" alt="Accounts" src="https://github.com/user-attachments/assets/9df96dda-5673-41d9-8a1d-94643caff339" />
  <br><sub><i>Accounts: several users, each with their own password and files.</i></sub>
</p>

<p align="center">
  <img width="800" alt="Live wallpaper and dynamic island" src="https://github.com/user-attachments/assets/99e5f68b-b34a-4f63-8f8a-7447164b270c" />
  <br><sub><i>Live wallpapers and the dynamic island for music, timers and updates.</i></sub>
</p>


---

## Updates

hyadeOS updates itself. To check manually: **Settings > Updates > Check for updates**.

Every release is checked before it is applied, and hyadeOS goes back to the previous version by itself if an update does not start.

<p align="center">
  <img width="800" alt="Updates settings" src="https://github.com/user-attachments/assets/43dfd719-d1ce-44b9-8ff7-5661281577e1" />
  <br><sub><i>Settings > Updates: check for new versions with one click.</i></sub>
</p>


---

## Versions and channels

- hyadeOS: <img width="35" height="12" alt="Frame 394" src="https://github.com/user-attachments/assets/0d5193b7-8dbe-46bd-b16e-4905b56d8c1f"/> 1.0 insiders public release
- Community: <img width="35" height="12" alt="Frame 397" src="https://github.com/user-attachments/assets/904da047-ba55-4aa4-9a56-a68082cb9d25" /> <img width="35" height="12" alt="Frame 394" src="https://github.com/user-attachments/assets/0d5193b7-8dbe-46bd-b16e-4905b56d8c1f"/> 1.0 Pre-Release candidate
- Insider: <img width="35" height="12" alt="Frame 395" src="https://github.com/user-attachments/assets/7a201959-1d01-43a0-b3e8-59b3e69ddd5f"/> 0.8.1 Insiders
- Private: <img width="51" height="12" alt="Frame 3s94" src="https://github.com/user-attachments/assets/67953a09-3730-47ed-a8cc-a6f108ec7e1f"/> <img width="35" height="12" alt="Frame 394" src="https://github.com/user-attachments/assets/0d5193b7-8dbe-46bd-b16e-4905b56d8c1f"/> 1.0 (STABLE TEST)
- DosVM: <img width="51" height="12" alt="Frame 398" src="https://github.com/user-attachments/assets/2c3ee65c-1eca-4044-a828-38adef1f7e5b" /> <img width="35" height="12" alt="Frame 394" src="https://github.com/user-attachments/assets/af19c8f1-6c57-4466-94f7-c5711f28dfd6" /> <img width="35" height="12" alt="Frame 399" src="https://github.com/user-attachments/assets/734b06c4-2b0d-497a-9161-cd13b6361d56" /> α0.5

Where to get what:

| You want...                      | Go to                                                        |
|----------------------------------|--------------------------------------------------------------|
| The installer and stable builds  | [hyadeOS/stable](https://github.com/hyadeOS/stable/releases) |
| Older versions                   | [hyadeOS/OTA](https://github.com/hyadeOS/OTA)              |
| The development code (this repo) | [hyadeOS/development](https://github.com/hyadeOS/development) |

> ⚠️ **This repository is the main development repo.** It holds the code we work on before compressing it into stable images. It is **not** meant to be used as your main system and is **not** ready for production. If you just want to use hyadeOS, use the installer above.

---

## Run from source (developers)

Requires Node.js 22.12 or newer.

```
git clone https://github.com/hyadeOS/development
cd development
npm install
npm run start-hidden.vbs
```

Electron starts the local backend, shows a boot screen while it checks readiness and preloads desktop images, and then opens the OS fullscreen. Quick Settings can shut down hyadeOS or reboot its kernel (restart `system/server.js`) without closing Electron; shutting down hyadeOS does not shut down the host computer. This starts the development Electron runtime and does not produce platform installer packages.

Platform launchers are also provided, all starting the same Electron shell (dependencies installed with `npm install` are required):

| Platform | Launcher                                                                  |
|----------|---------------------------------------------------------------------------|
| Windows  | double-click `start.bat`                                                  |
| Linux    | run `sh start.sh`                                                         |
| macOS    | open `start.command` (if needed, run `chmod +x start.command` once first) |

### Verbose boot (CLI only)

To show live startup stages over the boot logo:

```
npm run boot:verbose
npm run start-hidden.vbs
```

Verbose mode stays enabled across restarts until disabled with `npm run boot:quiet`. Check the current mode with `npm run boot:status`. Startup errors remain visible even when verbose boot is disabled.

---

## Build apps for hyadeOS

hyadeOS apps are web pages in a GitHub repository. The SDK gives them notifications, files (with the user's permission), the system theme and more. See the developer guide in the [hyadeOS organisation](https://github.com/hyadeOS).

---

## Organizations and custom builds

If you build hyadeOS for other specific devices (such as tablets or laptops) or for an organization, make sure every external service (e.g. update mirrors) is changed before publishing, otherwise the official generic one will overwrite yours at every update.

For organizations you can set up the **Temp** account, which is flushed at every logoff. It is useful when several people share a device (e.g. a library). The Temp account has no administrative rights and can't modify anything on the system. The backend is limited, and so are external services.

---

## Community

- Website: [hyadeos.github.io](https://hyadeos.github.io)
- TikTok: [@_hyadeos_](https://www.tiktok.com/@_hyadeos_)
- Report a bug or suggest a feature on our Discord, or open an issue here.

---

## License and credits

Licensed under the Apache License, Version 2.0. You may use this project if you give credit to the original creators and comply with the License. A copy is available at <http://www.apache.org/licenses/LICENSE-2.0>.

- This project uses open source, free fonts from Google Fonts. Google Fonts is a trademark of Google LLC; privacy docs are at <https://developers.google.com/fonts/faq/privacy>.
- This project uses open source, free, community-made Node/npm modules. All credit goes to their [authors](https://github.com/hyadeOS/#credits).
