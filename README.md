# tint

## Firebase setup
1. Authentication > Sign-in method > enable **Email/Password** (Anonymous is no longer needed).
2. Firestore Database > Rules > paste everything from `firestore.rules` > Publish.
3. Put your web config in `www/firebase-config.js`.

## Build the APK
Upload the files to GitHub > Actions > Build APK > run > download `tint-apk`.
