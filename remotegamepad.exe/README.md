# Remote Gamepad

Decompiled and restructured Android APK for remote gamepad control between devices.

## Changes
- Connection timelimit increased from 10 minutes to 2 hours in C7735a.java (zze) and AbstractC5216a.java (f18443a, f18450a).

## Structure
- src/main/
  - AndroidManifest.xml
  - java/com/remotegamepad/defpackage/ (*.java with timeout mods)
  - res/ (add if available)
  - assets/ (add if available)
Root: README.md, .gitignore, TODO.md
GitHub-ready, apktool b compatible.

## Build
Use apktool: `apktool b . -o remotegamepad_mod.apk`

Ignore large binaries (.dex, .apk, etc.) via .gitignore.

