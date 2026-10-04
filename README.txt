FAMILY EXPENSES - ANDROID APP PROJECT
=====================================

HOW TO MAKE THE .APK (one time, on a PC)
1. Install Android Studio (free): https://developer.android.com/studio
2. Unzip this folder. In Android Studio choose File > Open and select the
   "FamilyExpensesApp" folder.
3. Wait for "Gradle sync" to finish (needs internet the first time).
   If it asks to use the Gradle wrapper or to upgrade anything, accept.
4. Menu: Build > Build Bundle(s) / APK(s) > Build APK(s).
5. Click "locate" in the pop-up. The file is app-debug.apk
   (app/build/outputs/apk/debug/).
6. Send app-debug.apk to your phone (WhatsApp, Drive, USB). Open it and allow
   "Install from this source" when Android asks.

CHANGING THE APP LATER
The whole app is one file: app/src/main/assets/index.html
Replace it with a new version and build the APK again.

GOOD TO KNOW
- Expenses entered in the app are saved inside the app on that phone.
  They are separate from the website version.
- Uninstalling the app deletes its saved expenses.
- For the Google Play Store you would need a signed release build.
- Minimum Android version: 8.0.
