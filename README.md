# GradlePluginLibTest
https://issuetracker.google.com/issues/133782953

Note1: the libs are included when we use gradle plugin 3.4.2, but not when we use plugin 3.5.0-rc01

Note2: the problem only occurs when deploying the APK to a device/emulator. If you just Rebuild (within Android Studio) then the libs are correctly included. So, to experience this bug, you need to Run... (and presumably select a 64 bit device)
