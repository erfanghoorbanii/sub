# Ghab (Android)

Android app for Ghab Captions: automatic cinematic captions for Shorts and Reels, in Persian and English.

## Get the APK without installing anything (GitHub)
1. Create a free account at github.com and make a new repository.
2. Upload every file in this folder (including the hidden `.github` folder).
3. Open the **Actions** tab. The "Build Android APK" job runs by itself (about 5 minutes).
4. Open the finished run and download **Ghab-APK**. Unzip it and install the `.apk` on your phone
   (allow "Install unknown apps" for your browser or file manager when Android asks).

## Or build in Android Studio
Open this folder in Android Studio and choose Build > Build APK(s).

## Notes
- Exported videos go to `Movies/Ghab`, SRT files to `Download/Ghab`.
- The speech model downloads once on first use and is kept on the phone.
- The release APK is signed with the debug key. Sign it with your own key before publishing on Google Play.
