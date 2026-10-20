# MyChatApp

A simple Android group chat app with one public chat room, built on Firebase. There's no server code of its own.

## Features
- Sign-up and sign-in with FirebaseUI Auth
- Real-time group messages stored in Firebase Realtime Database (`ChatMessage` model)
- Single chat room open to all signed-in users

## Tech stack
Java, Android SDK (compileSdk 28, minSdk 16), Firebase Auth, Realtime Database, FirebaseUI.

## Build
1. Create a Firebase project with Authentication and Realtime Database enabled.
2. Put your own `google-services.json` in `app/`.
3. Open the project in Android Studio and run it, or use `./gradlew assembleDebug`.

## Credits
Built by following [How to Create an Android Chat App Using Firebase](https://code.tutsplus.com/tutorials/how-to-create-an-android-chat-app-using-firebase--cms-27397) (Envato Tuts+).
