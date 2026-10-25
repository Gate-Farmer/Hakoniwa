# Hakoniwa 1.60.0 — Quest 3 Android APK

This Android app wraps the supplied **Hakoniwa Fresh 1.60.0** HTML in a portrait WebView. It is a **2D Android application shown in a Quest panel**, not a native stereoscopic VR game.

## Build using GitHub on a phone

1. Upload **all project files, including the `.github` folder**, to the root of your repository. You can use the GitHub website **Add file → Upload files** (extract this ZIP first), or upload using GitHub Desktop/git from a computer.
2. Push to `main`, or visit **Actions → Build Hakoniwa Quest 3 APK → Run workflow**.
3. Open the completed workflow and download the **Hakoniwa-1.60.0-Quest3-APK** artifact ZIP.
4. Extract `app-debug.apk` and sideload it to your Meta Quest 3 using SideQuest or `adb install app-debug.apk`.

The debug APK is signed automatically by the Android build tools, so it installs without Google Play. It is **not a Play Store release build**. The app's browser localStorage persists on-device until app storage is cleared/uninstalled. Internet is needed for Google Fonts and any external game services.

**Package ID**: `com.hakoniwa.quest`. **Display orientation**: portrait. **Version**: 1.60.0.
