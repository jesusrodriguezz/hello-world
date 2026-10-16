# Streaks: a phone app without the App Store

`docs/` holds a small habit tracker built as a **Progressive Web App (PWA)**.
You open it in your phone's browser and add it to your home screen. From then on
it launches full-screen with its own icon, works offline, and keeps your data on
the device. No App Store, no developer account, no sideloading.

## Put it online (one time, free)

1. On GitHub, open this repo → **Settings** → **Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**, pick the
   branch, folder **`/docs`**, and click **Save**.
3. After a minute your app is live at
   `https://jesusrodriguezz.github.io/hello-world/`.

## Install it on your phone

- **iPhone (Safari):** open the link → **Share** → **Add to Home Screen**.
- **Android (Chrome):** open the link → **⋮** → **Add to Home screen** / **Install app**.

## Notes

- Your habits are stored only on your phone (`localStorage`). Deleting the
  app from the home screen or clearing Safari/Chrome site data erases them.
- After changing any file in `docs/`, bump `VERSION` in `docs/sw.js` so
  installed copies pick up the update.
