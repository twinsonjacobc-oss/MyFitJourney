MY FIT JOURNEY — ANDROID PROJECT
=================================

This is an Android Studio project wrapping your personalised weight-loss tracker
in an Android app for your Samsung Galaxy S23 Ultra.

IMPORTANT
---------
This is the Android source project, not a compiled APK. This workspace does not
have the Android SDK / Android Gradle build tools installed, so an APK could not
be compiled or signed here.

BUILD A DEBUG APK
-----------------
1. Install Android Studio on a computer.
2. Open Android Studio and choose "Open".
3. Select this folder: MyFitJourneyAndroid
4. Allow Android Studio to sync/download the Android Gradle Plugin and SDK
   components it requests (compile SDK 35).
5. Connect your phone with USB debugging enabled, or use Build > Build Bundle(s)
/ APK(s) > Build APK(s).
6. Android Studio creates the APK at:
   app/build/outputs/apk/debug/app-debug.apk
7. Transfer app-debug.apk to your S23 Ultra, open it, and allow installation
   from that source if Android asks.

APP FEATURES
------------
- Daily tick-off checklist for meals, water, walking, workout and sleep
- First-week commitment checklist
- Weekly progress review
- Personal weight log and target progress
- Local browser storage on the device

NOTES
-----
- This is a basic offline WebView app; no account or cloud sync is included.
- Keep the app installed and avoid clearing its app data to retain local records.
- For sharing records between devices, export/backup support should be added.
