# LinkUp Android starter project

This is an Android Studio project that wraps the LinkUp mobile-friendly prototype in a native Android shell.

## Build an APK
1. Install Android Studio on a computer.
2. Extract this project ZIP.
3. In Android Studio choose **Open** and select the extracted `LinkUp_Android_Project` folder.
4. Allow Gradle sync to finish and install any requested Android SDK components.
5. Use **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
6. Android Studio will show where the debug APK was saved; transfer it to your Android phone to install it.

## Current scope
This project packages the existing local prototype. It does not yet provide real user registration, cloud data, online messaging, photo/video uploads, push notifications, or calls. Those require a secure backend and additional implementation. Do not publish this prototype as a production social network yet.

## Technical notes
- Java Android activity with WebView
- Interface bundled locally in `app/src/main/assets/index.html`
- Minimum Android version: Android 6.0 (API 23)
- No internet permission is requested in this demo because its current interface is local-only
