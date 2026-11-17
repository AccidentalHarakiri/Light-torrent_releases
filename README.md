# Light_torrent

A lightweight torrent client for Windows. No ads, no telemetry😊

## Download

**Version 0.2.4** (2026-11-11) — [Light_torrent_0.2.4_x64-setup.exe](https://github.com/AccidentalHarakiri/Light-torrent_releases/releases/download/v0.2.4/Light_torrent_0.2.4_x64-setup.exe), 4.4 MB

Windows 10 and 11, 64-bit. Installs for all users of the computer (asks for administrator
rights). After that the app updates itself: it shows a "New version available" window, and only
updates signed by the developer are installed.

### What's new in 0.2.4
- Seeding engine fixes
- Performance improvements
- General improvements

All versions are on the [Releases](https://github.com/AccidentalHarakiri/Light-torrent_releases/releases) page.

## "Windows protected your PC"

The installer is not signed with a paid certificate, so Windows may show this window on first
launch. Click **"More info" → "Run anyway"**.

To make sure the file has not been tampered with, compare its SHA-256 with the one below. In PowerShell:

```
Get-FileHash .\Light_torrent_0.2.4_x64-setup.exe -Algorithm SHA256
```

SHA-256: `ac97b726356342a68698c825ed70dba452c1ee253ff3dd822fcfc681c3f8199f`

## Security

Found a vulnerability? Please report it privately as described in [SECURITY.md](SECURITY.md).

## License

The app is free; the source code is closed. Licenses of the open-source libraries it uses are in
the app: Settings → "Licenses".


## Suggestions
Have suggestions? Let’s discuss) The client is still in development.
