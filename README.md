<p align="center">
  <img src="assets/logo.png" width="120" alt="MeetingTune logo" />
</p>

# MeetingTune

**MeetingTune** is a desktop app that plays your chosen tune before meetings and shows a live countdown so you're never caught off guard. The tune isn't just a reminder — it's a vibe shift. That last minute before a meeting doesn't have to feel like dread; MeetingTune fills it with a track that gets your head in the game so you show up energised and ready.

<p align="center">
  <img src="assets/menubar-preview.png" width="480" alt="MeetingTune live countdown in the macOS menu bar" />
</p>

## Download

| Platform | Architecture | Download |
|----------|-------------|----------|
| macOS | Apple Silicon (M1/M2/M3/M4) | [MeetingTune-1.0.0-arm64.dmg](https://github.com/nickattack97/meetingtune/releases/latest/download/MeetingTune-1.0.0-arm64.dmg) |
| macOS | Intel (x64) | [MeetingTune-1.0.0-x64.dmg](https://github.com/nickattack97/meetingtune/releases/latest/download/MeetingTune-1.0.0-x64.dmg) |
| Windows | x64 | [MeetingTune-Setup-1.0.0-x64.exe](https://github.com/nickattack97/meetingtune/releases/latest/download/MeetingTune-Setup-1.0.0-x64.exe) |

## Installation

### macOS

> **Prerequisites — sync your calendar first**
> MeetingTune reads events from the macOS Calendar app. Before launching, make sure the calendar account you want to use (e.g. Microsoft 365, Google, Exchange) is signed in and syncing in the macOS Calendar app:
> 1. Open **Calendar** → **Settings** (⌘,) → **Accounts**.
> 2. Click **+** and sign in to your calendar account if it isn't listed.
> 3. Ensure the account is enabled and its calendars are checked in the Calendar sidebar.
> 4. Wait for events to sync before launching MeetingTune.

1. Download the `.dmg` for your architecture above.
2. Open the `.dmg` and drag **MeetingTune** to your Applications folder.
3. Launch MeetingTune — grant **Calendar** access when prompted on first launch.

> **"MeetingTune is damaged and can't be opened" ?**
> This is a macOS Gatekeeper restriction, not actual damage — it appears because the app is not yet notarised with an Apple Developer certificate. Run this one-time command in Terminal after dragging the app to Applications, then relaunch normally:
> ```bash
> xattr -cr /Applications/MeetingTune.app
> ```

### Windows
1. Download `MeetingTune-Setup-1.0.0-x64.exe` above.
2. Run the installer and follow the on-screen instructions.
3. Launch **MeetingTune** from your desktop or Start Menu.

## Requirements

- **macOS**: 12 Monterey or later, Xcode Command Line Tools (for Calendar helper — installed automatically on first launch)
- **Windows**: Windows 10 or later, Microsoft 365 / Exchange account for calendar access

## License

© 2026 MeetingTune. All rights reserved.
