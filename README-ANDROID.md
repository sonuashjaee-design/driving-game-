# City Driver 3D Android build

This repository now includes a native Android WebView wrapper for the existing HTML game.

## Build
Every push to `main` starts the **Build City Driver 3D APK** workflow. You can also start it manually from the GitHub Actions tab.

When the run completes:
1. Open the repository's **Actions** tab.
2. Open the latest **Build City Driver 3D APK** run.
3. Scroll to **Artifacts**.
4. Download **City-Driver-3D-APK** and extract `app-debug.apk`.
5. Transfer the APK to your Android phone and install it. Android may ask you to allow installs from that source.

The game uses Three.js from a CDN, so an internet connection is required when playing unless the game is later changed to bundle that library locally.
