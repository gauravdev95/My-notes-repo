# My Notes

Simple offline notes app for Android. Create notes, write, save — everything stays on your phone.

## Auto-update

The app checks `version.json` in this repo on every launch. When `versionCode` there is
higher than the installed app's, it offers a one-tap download + install of the APK
linked in `apkUrl`.

## Files

- `mynotes.apk` — latest signed APK (install over the previous version; notes are kept)
- `version.json` — update metadata read by the app
