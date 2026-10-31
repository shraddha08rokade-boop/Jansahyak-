JANSAHAYAK ANDROID APK PROJECT
================================

This packages the JanSahayak educational prototype in a basic Android WebView app.
The HTML app runs locally inside the APK. Internet is only needed when opening
external official-government links.

BUILD THE APK FOR FREE WITH GITHUB ACTIONS (PHONE-FRIENDLY ROUTE)
-----------------------------------------------------------------
1. Sign in to https://github.com/ and create a NEW PUBLIC or PRIVATE repository
   named JanSahayak.
2. Extract this ZIP on your phone using your file manager.
3. Upload the extracted PROJECT FILES and FOLDERS to the repository's main branch.
   Keep the folder structure exactly as it is. The .github folder is important.
4. Open the repository on GitHub, choose the Actions tab.
5. If asked, enable GitHub Actions for the repository.
6. Select "Build JanSahayak APK" and tap "Run workflow".
   (A push to the main branch also starts a build automatically.)
7. Wait for the workflow to finish successfully.
8. Open that workflow run, scroll to Artifacts, and download
   "JanSahayak-debug-apk".
9. Extract the downloaded artifact ZIP. It contains app-debug.apk.
10. Open the APK on your Android phone and allow installation from that source
    if Android asks. Only install APKs you built or trust.

PROJECT DETAILS
---------------
App name: JanSahayak
Package: org.jansahayak.app
Minimum Android: Android 6.0 (API 23)
Build type: Debug APK for classroom demonstration
Main app page: app/src/main/assets/index.html

IMPORTANT
---------
This is a demonstration app, not an official government app. Scheme information
is illustrative and may change. Users should verify eligibility, documents,
benefits and application steps on the linked official government portals.
The debug APK is suitable for testing/classroom demonstration, not Play Store
publication. A release APK requires signing and a separate release build.
