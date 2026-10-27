# FAVE downloads

## [Download FAVE 1.0.6 beta](https://github.com/mrjellifish/FAVE-releases/releases/tag/v1.0.6-beta.1)

### Windows x64

Download **FAVE-1.0.6-Windows-x64-Setup.exe**. Save your session, close all DAWs, run Setup, choose your VST3 folder, then reopen your DAW and rescan VST3 plugins if needed. Administrator permission is required. Setup installs the plugin and its updater.

### macOS — Intel and Apple Silicon

Download **FAVE-1.0.6-macOS-universal.zip**, unzip it, open **FAVEUpdater.app**, choose your VST3 folder, close your DAWs and click **Install FAVE**. It remembers the selected folder and retains the updater for future releases. Reopen the DAW and rescan if needed.

Version 1.0.6 adds a folder chooser to the installers and updater, remembers your choice, and opens the editor 30% smaller (840 × 420). Choose the parent folder that should contain **FAVE.vst3**, not the bundle itself. Enable custom VST3 folders in your DAW when needed. Audio processing is unchanged.

### Future updates

Use **UPDATES** inside FAVE. On the first window opened in a DAW session, an automatic check also runs if at least a day has passed. A newer signed release enables **UPDATE AVAILABLE**. The companion downloads and verifies it, waits for you to save and quit the DAW, then starts installation in your remembered folder. You can choose a different folder in the installer/updater. It never kills your DAW. Windows still shows Setup/UAC. An optional button reopens the DAW after installation; unsaved projects cannot be restored.

No GitHub account is required. Existing 1.0.3 users must install this complete package once to add the updater. Download installers from the versioned release above; the separate update-channel-beta release contains metadata for the plugin, not installers.

### Beta status

Windows installers are unsigned, so Windows may show an unknown-publisher warning. Mac apps are ad hoc signed for integrity, not Developer ID signed or notarized, so Gatekeeper may block them. Publisher signing accounts are not configured yet. Update signatures authenticate future downloads but do not remove OS publisher warnings.

Automated audio tests and updater verification passed on both platforms. CI installed and loaded the Windows VST3, checked custom-folder migration and remembered locations, and rejected updating a loaded plugin. Mac installation/upgrade tests and both CPU architectures were verified. Real DAW testing by beta users is still needed. Please report OS, DAW/version, scan/load results and audio/UI issues. Auto Gain remains disabled.

Source code is maintained separately in a private repository.
