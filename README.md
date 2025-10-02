# SNU_app_capture_unlocked

latest: https://github.com/min09357/SNU_app_capture_unlocked/releases/latest

Just download and install apk file.

Below is how to patch app. You don't have to read!!

## How to patch?

### Prerequisite

Shizuku (PlayStore) or ADB (PC. https://dl.google.com/android/repository/platform-tools-latest-windows.zip?hl=ko)

LSPatch (https://github.com/JingMatrix/LSPatch). Official version is outdated.

Xposed (https://github.com/VarunS2002/Xposed-Disable-FLAG_SECURE)

### Patch

1. Activate shizuku. In PC,
```
C:\adb\adb shell sh /storage/emulated/0/Android/data/moe.shizuku.privileged.api/start.sh
```
 with administor shell. In mobile, follow the guide in app.

2. LsPatch - manage (second tab at the bottom) - select app

3. Combined(통합) - Include module(모듈 포함) - select Xposed

4. Check overlay version code(버전 코드 덮어씌우기)

5. Patch and install

### Other ADB commands

#### Camsung

https://github.com/ericswpark/camsung/releases

```
adb install --bypass-low-target-sdk-block app-release.apk
```



