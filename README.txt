MYChat -> Android APK (no Android Studio needed)

1. Create a free account at github.com and make a NEW repository (any name).
2. Click "uploading an existing file" and drag in EVERYTHING from this folder
   (www, .github, package.json, capacitor.config.json, .gitignore). Commit.
   NOTE: the ".github" folder must be uploaded too (it holds the build recipe).
3. Open the repo -> "Actions" tab -> "Build APK" -> wait ~5-8 minutes.
4. Open the finished run -> scroll to "Artifacts" -> download "MYChat-apk" (zip).
5. Unzip, send app-debug.apk to your phone, install it
   (allow "Install unknown apps" when asked).
6. Open the app and tap ALLOW on the notification prompt.

To change the chat later: edit www/index.html in GitHub and commit; a new APK builds automatically.
