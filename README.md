CTPViewerApp - Android WebView wrapper for index.html
----------------------------------------------------
What this is:
- An Android Studio app skeleton that opens the provided index.html from app/src/main/assets/index.html inside a WebView.
- Network access is allowed. The WebView enables JavaScript and localStorage.

How to build:
1. Download and unzip this project (CTPViewerApp.zip).
2. Open the folder in Android Studio (File → Open).
3. Let Android Studio sync Gradle (it may ask to install/update components).
4. Build → Run or Build → Build Bundle(s) / APK(s) → Build APK(s).

Notes:
- The project uses Kotlin and AndroidX.
- The Gradle wrapper files are not included; Android Studio can generate them if missing.
- To produce a signed release APK, follow Android Studio's signing flow (Build → Generate Signed Bundle/APK).
