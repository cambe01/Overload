# Overload – offline gym tracker for iPhone

A Home Screen web app. After you install it once, it runs fully offline. All data stays on the phone (in the app's local storage).

## Install on your iPhone (one time)
Offline mode needs the app to be served over HTTPS once. Free option:

1. Create a GitHub repo (e.g. `overload`) and upload every file in this folder.
2. Repo **Settings → Pages → Deploy from branch → main / root**. You get a URL like `https://<you>.github.io/overload/`.
3. On the iPhone, open that URL in **Safari** → Share → **Add to Home Screen**.
4. Open it from the Home Screen icon once while online. After that it works with no internet.

## Updating the app
Change the files, bump `CACHE` in `sw.js` (e.g. `overload-v2`), and push. The phone picks up the new version the next time you open the app while online.

## Backups
Settings → Export backup → save to Files/iCloud. Import restores it. Your data is kept if you update the app. It is lost if you delete the Home Screen app.
