# ShopRefresh

**Automated Secret Shop refreshes for Epic Seven on Windows.**

ShopRefresh watches the Epic Seven Secret Shop, buys **Covenant Bookmarks** and **Mystic Medals** whenever they appear, and refreshes with skystones until your limits are reached. It tracks every run, compares your drops with the official rates, and runs entirely on your own PC.

This repository hosts the official Windows releases.

## Download

Get the latest **`ShopRefresh-vX.Y.exe`** from the [Releases page](https://github.com/asunakiyo/ShopRefresh/releases/latest). Place it in its own folder and double-click it. No installation or Python is needed. Approve the Administrator prompt, because the game may ignore clicks otherwise.

**Requirements:** Windows 10 or 11, and the Epic Seven PC client in borderless or maximized window mode.

## Verify your download

Each release lists a SHA-256 checksum, a fingerprint of the exact file that was published. To confirm your copy is genuine and complete, run this in PowerShell from the download folder and compare the result with the checksum on the release page:

```powershell
Get-FileHash .\ShopRefresh-v0.5.exe -Algorithm SHA256
```

You can also run `ShopRefresh-v0.5.exe --self-test`, which checks the app without touching the game and writes `selftest.txt` ending in `PASS`.

## Updating

From v0.6 onward, the app shows a banner when a new version is available, with **Download**, **What's new**, and **Skip**. Put the new exe in the **same folder** as the old one and run it. Your `settings.json` and `lifetime_stats.json` live in that folder, so they carry over. Then delete the old exe.

## Privacy

ShopRefresh stores its settings and statistics as plain files next to the exe. It stores no passwords or account details. Its only network request is an optional update check against this repository's releases, which can be turned off in Settings.

## Disclaimer

ShopRefresh is an unofficial, fan-made tool. It is not affiliated with, endorsed by, or supported by Smilegate or Epic Seven. Using third-party tools, macros, or bots may violate the game's Terms of Service and may result in account suspension or a permanent ban. Use this tool at your own risk. The authors accept no responsibility for any consequences arising from its use.
