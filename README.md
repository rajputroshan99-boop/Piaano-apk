# Little Melody Piano — Android App Project

This project wraps your latest **Little Melody Piano** web app (`app/src/main/assets/index.html`) inside a native Android WebView app ready to compile into an `.apk`.

## Option 1: Build APK in Android Studio (Easiest on PC/Mac)
1. Unzip `LittleMelodyPiano_Android.zip`.
2. Open **Android Studio** and click **Open**, then select the unzipped `LittleMelodyPiano_Android` folder.
3. Wait for Gradle Sync to finish.
4. Go to **Build → Build Bundle(s) / APK(s) → Build APK(s)**.
5. Copy `app/build/outputs/apk/debug/app-debug.apk` to your Android phone and tap it to install.

## Option 2: Build APK Free in the Cloud (No Android Studio Needed)
1. Create a free repository on GitHub and upload all files from this folder (including `.github/workflows/build-apk.yml`).
2. Open the **Actions** tab on GitHub — the **Build Android APK** workflow will run automatically.
3. Download the **LittleMelodyPiano-debug-apk** artifact and install `app-debug.apk` on your Android phone.
