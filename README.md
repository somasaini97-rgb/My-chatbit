# JARVIS Android App

This project wraps the web application from `jarvis.zip` in a native Android WebView.

## Entry page
`app/src/main/assets/web/jarvis/ui/index.html`

## Build
Open this folder in Android Studio, let Gradle sync, then choose:
**Build → Build App Bundle(s) / APK(s) → Build APK(s)**

The app requests microphone permission for browser-based voice input.

## Important
If the original JARVIS app calls a Python/Node backend on `localhost`, Android cannot reach the computer's localhost from the phone. Set the backend URL to a reachable HTTPS server or the computer's LAN IP before using backend features.
