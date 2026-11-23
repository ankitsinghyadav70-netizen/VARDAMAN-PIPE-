# Vardaman Safetech – Android app

Offline Android app holding three tools: Truss pipe calculator, Truss load calculator and Quotation.
The pages live in `app/src/main/assets/www/`. Saved PDFs/CSVs go to **Downloads › Vardaman**.

## Get the APK without installing anything (GitHub)
1. Create a new repository on github.com and upload everything in this folder (keep the `.github` folder).
2. Open the **Actions** tab. The "Build APK" run starts by itself (or press *Run workflow*).
3. When it turns green (about 5 minutes), open the run and download **Vardaman-Safetech-APK**. Unzip it to get `Vardaman-Safetech.apk`.

## Or build on a PC with Android Studio
Open this folder in Android Studio, wait for sync, then *Build › Build APK(s)*.

## Install on the phone
Copy the APK to the phone, tap it, and allow "Install unknown apps" for your file manager when asked.

The APK is signed with a debug key, which is fine for your own phones. Use your own signing key before publishing on Google Play.
