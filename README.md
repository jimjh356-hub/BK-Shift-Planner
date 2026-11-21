# Shift Planner for Android

A small Android app that shows your Burger King shifts week by week and lets you edit, add and delete them. Everything is saved on your phone and works without internet.

## Get the app on your phone

You need a free GitHub account. GitHub builds the app for you; there is nothing to install on a computer.

1. Go to **github.com**, sign in (or create a free account).
2. Tap **+ → New repository**. Name it `shift-planner`. Choose **Private** if you like. Tap **Create repository**.
3. On the new repository page, tap **uploading an existing file**.
4. Unzip this project on your computer. Drag **everything inside the folder** into the upload page. That includes the hidden folder `.github`.
   - If `.github` did not upload: tap **Add file → Create new file**, type `.github/workflows/build.yml` as the name, and paste in the text of `.github/workflows/build.yml` from this project.
5. Tap **Commit changes**.
6. Open the **Actions** tab. The build starts by itself and takes about 3 to 5 minutes. A green tick means it worked.
7. Go back to the main page of the repository. On the right, open **Releases**, then the newest one, and download **ShiftPlanner.apk** on your phone.
8. Open the downloaded file. Android will ask to allow installing apps from this source. Allow it, then tap **Install**.

## Notes

- Your shifts start as the schedule from your rosters (9 Nov to 28 Jan). Changes you make are saved on the phone only.
- Uninstalling the app or clearing its data removes your changes.
- Needs Android 8 or newer.
- If the build in step 6 shows a red cross, open that run, copy the error message and send it to Claude.
