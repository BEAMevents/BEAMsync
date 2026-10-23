# BEAMsync

Keeps folders in sync between Macs and PCs on the same network. Change a file on one computer and it appears on the others within seconds. No internet or cloud account needed. By [BEAM Events](https://beamevents.com).

This repository only holds the **installers and updates**.

## Download
Get the latest version from **[Releases](https://github.com/BEAMevents/BEAMsync/releases/latest)**:

- **BEAMsync-Setup-x.y.z.exe** (Windows) installs BEAMsync and **updates itself automatically**. Use this one on PCs.
- **BEAMsync-Portable-x.y.z.exe** (Windows) runs without installing. It tells you when a newer version is out, but doesn't update itself.
- **BEAMsync-x.y.z-mac-arm64.dmg** (Mac, Apple Silicon). It tells you when a newer version is out; download the new .dmg to update.

The Windows installers aren't code-signed yet, so SmartScreen may warn on first launch: click **More info → Run anyway**. When Windows Firewall asks, allow BEAMsync on **Private networks**. On Mac, click **Allow** when asked to let BEAMsync find devices on your local network.

## Updates
The installed Windows version checks for updates in the background and shows **Update x.y.z ready** in its header. Click it, then **Install & restart**. Updates never install while files are being copied.
