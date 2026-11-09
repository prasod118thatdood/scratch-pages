Build: open this folder in Android Studio, let it sync, then Build > Build APK(s).
Install: adb connect <fire-tv-ip>:5555 ; adb install -r app-debug.apk
Edit the launcher UI in app/src/main/assets/index.html (package names in data-pkg).
