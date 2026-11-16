TERAPHON DLNA SIMULATOR - TEST BUILD SOURCE

Large high-contrast Android receiver app. Android 8+ (Galaxy Tab A7 supported).
This ZIP is a source project, NOT a prebuilt APK.

BUILD APK ON GITHUB:
1. Upload all files/folders to a new GitHub repository (including .github/workflows).
2. Open Actions -> Build TERAPHON DLNA Simulator APK -> Run workflow.
3. Download artifact TERAPHON_DLNA_SIMULATOR_APK.
4. Unzip artifact and install app-debug.apk on old Galaxy Tab A7.
5. Connect both tablets to same Wi-Fi, open simulator on A7, keep it foreground.
6. Search for "Cambridge NP30 TEST - TERAPHON" in TERAPHON DLNA list.

LIMITATIONS: This is a prototype MediaRenderer with basic SSDP and AVTransport. It does NOT emulate real Cambridge NP30 firmware, and playback of infinite-length WAV streams depends on Android MediaPlayer support. UPnP eventing and full SCPD action argument definitions are not implemented. Some control points may reject this prototype. Google Cast app is not modified.
