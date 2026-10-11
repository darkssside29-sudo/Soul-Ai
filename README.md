# Soul AI — Android starter project

This is a starter Android Studio project, not a finished AI dubbing app.

## Included
- Dark Soul AI starter UI
- Pick and play a local video using Android's document picker and AndroidX Media3
- Test the device's installed Hindi Text-to-Speech voice (if available)

## Not included yet
- Automatic English speech transcription
- Translation of the video's speech to Hindi
- Synchronised Hindi voice replacement/mixing
- YouTube in-app playback/dubbing integration
- APK binary

## Build
1. Install Android Studio on a computer.
2. Open this folder in Android Studio.
3. Let Gradle sync and install any requested Android SDK platform (compile SDK 36).
4. Connect an Android phone with developer options/USB debugging enabled, or use Build > Build APK(s).

No special storage permission is required for the document-picker flow.

## Notes
The Hindi TTS voice depends on the Android speech engine installed on the device and may not sound natural on every phone. The app currently speaks a fixed Hindi sample; it does not translate a video's audio automatically.
