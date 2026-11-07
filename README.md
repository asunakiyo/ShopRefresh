# Secret Shop Refresh Bot

Windows app that refreshes the Epic Seven Secret Shop and buys Covenant Bookmarks and Mystic Medals for you, with honest drop-rate stats.

## Download

Get **ShopRefresh-vX.Y.exe** from the [latest release](https://github.com/asunakiyo/ShopRefresh/releases/latest). Put it in its own folder and double-click it. No install needed. It asks for Administrator because the game may ignore clicks otherwise.

## Updating

The app tells you when a new version is out. Download the new .exe into the **same folder** and run it. Your `settings.json` and `lifetime_stats.json` live in that folder, so your settings and lifetime stats carry over. Then delete the old .exe.

## Check a download

Run `ShopRefresh-vX.Y.exe --self-test`. It writes `selftest.txt`, which should end in `PASS`. Each release lists the file's SHA-256.

This repo only holds the releases.
