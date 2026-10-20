# Subpar Content for Premiere Pro

The Subpar Content panel for Adobe Premiere Pro. It imports Twitch stream markers from a CSV file and exports a sequence's marker timestamps.

## What you need

- Adobe Premiere Pro 25.6 or later
- The Creative Cloud desktop app, installed and signed in
- Premiere Pro opened at least once on this computer before you install

## Install it (first time)

1. Download `SubparContent-<version>.ccx` from the [latest release](https://github.com/NotJoeyBlack/subpar-content-releases/releases/latest).
2. Double-click the file. Creative Cloud opens.
3. Creative Cloud warns that the plugin isn't from the Adobe Marketplace. Continue anyway, then click **Install**. Your computer may ask for an administrator password.
4. Restart Premiere Pro.
5. Open the panel from **Window > UXP Plugins > Subpar Content**.

## Updates

The panel checks for a new version when it opens and every few hours after that. When one is ready, a banner appears at the top of the panel:

1. Click **Update**.
2. Premiere Pro asks whether the panel can open the downloaded file. Allow it. You can tell it to remember your choice.
3. Creative Cloud opens. Click **Install** if it asks.
4. Restart Premiere Pro.

The bottom of the panel shows which version you have. Click **Check for updates** there to check right away.

If the update doesn't start, the download page opens in your browser instead. Download the `.ccx` file and double-click it, the same way as the first install.

## If something goes wrong

- **Don't uninstall before updating.** Installing a new version replaces the old one, and uninstalling first deletes the panel's saved settings.
- **The panel isn't in the Window menu:** restart Premiere Pro, then look under **Window > UXP Plugins**.
- **Double-clicking the `.ccx` does nothing:** make sure the Creative Cloud desktop app is running and you're signed in, then try again.

## About this repository

This repository only holds released packages, not source code. Installed panels read `latest.json` to find the current version and download it from the `releases/` folder. These files are published by the release script, so don't edit them by hand.
