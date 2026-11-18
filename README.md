# Fokus
Offline Pomodoro timer for Android 13 and later. Includes Swedish and English, configurable intervals, lock-screen controls and light and dark themes.

## Build version 1.0.2
Install a JDK (17 or later), Android SDK Platform 36, Android Build Tools 35.0.0 and zip. Set ANDROID_HOME to your SDK directory and run ./build.sh in Bash. The unsigned output is build/aligned.apk. Sign with your own Android keystore using apksigner to install a personal build.

The bundled HTML supplies the interface. Home.java hosts it locally and Timer.java manages alarms, notifications and state. This snapshot targets API 34.
