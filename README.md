# BlackTools

Downloads for BlackTools on Mac and Windows. This repository holds only release files.

**[Download the latest version →](https://github.com/IkhmalHishyam/black-tools-releases/releases/latest)**

| Computer | File |
|---|---|
| Mac (Apple Silicon or Intel) | `BlackTools_<version>_universal.dmg` |
| Windows 10 or 11 | `BlackTools_<version>_x64-setup.exe` |

## First install

### Mac

BlackTools isn't notarized by Apple, so macOS says it "could not verify" the .dmg is free of malware and won't open it. Get past that in either of two ways.

**Quickest: one Terminal command.** Before opening the .dmg, run this in Terminal (adjust the version if yours differs):

```bash
xattr -d com.apple.quarantine ~/Downloads/BlackTools_0.1.1_universal.dmg
```

Then open the .dmg and drag BlackTools to Applications. It opens without any warning.

**Or with clicks:**

1. Open the .dmg. When the warning appears, click **Done**, not Move to Trash.
2. Open **System Settings → Privacy & Security**, scroll down to the line saying the .dmg was blocked, click **Open Anyway** and enter your Mac password.
3. Drag BlackTools to Applications and open it. macOS blocks the app once more: repeat step 2 for BlackTools.

### Windows


Run the setup .exe. If SmartScreen warns about an unknown publisher, click **More info → Run anyway**.

## Updates

BlackTools checks for new versions on its own. When one is out, **Update to …** appears at the bottom of the sidebar; click it and BlackTools updates and restarts. Updates never show the macOS warning. You can also click **Check for updates** there.

Ignore `.app.tar.gz` and `latest.json` in each release: the updater uses them.
