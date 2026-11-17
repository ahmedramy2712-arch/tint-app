# tint

## Before you build (Firebase, one time)
1. Authentication > Sign-in method > enable **Email/Password**.
2. Firestore Database > Rules > paste everything from `firestore.rules` > Publish.
3. Open `www/firebase-config.js` and paste your Firebase web app config over the PASTE_HERE values.
   (If you already have a repo with your config filled in, keep your own `firebase-config.js`.)

## Build the APK (no Android Studio)
1. Make a GitHub repo and upload ALL the files from this folder, including the hidden `.github` folder.
2. Repo > Actions > "Build APK" > Run workflow. Wait ~5 minutes.
3. Open the finished run > Artifacts > download **tint-apk** > unzip > `app-debug.apk`.
4. Install it on your phone (allow "install unknown apps").
