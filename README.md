# My Little Diary ♡

A soft, private diary app with a mood calendar, mood themes, dreamy music, and writing prompts.

- Every page is saved with its date and time
- A calendar you can swipe through. Tap a day to read what you wrote
- 9 colour themes, or let the colours follow your mood
- Favourites, search, mood filter, "on this day" memories, streaks
- Works offline once installed
- **Private:** your pages are stored only on your device. Nothing is uploaded anywhere.

## Install it on your phone

1. Open the app link (see below) in **Safari** on iPhone, or **Chrome** on Android.
2. iPhone: tap **Share → Add to Home Screen**.
   Android: tap **⋮ → Install app** (or **Add to Home screen**).
3. Open it from the home screen icon. It runs full-screen like a normal app.

## Put it online with GitHub Pages (free)

1. Sign in at github.com and click **New repository**. Name it `little-diary` and set it to **Public**. GitHub Pages needs public on free accounts. Only the app's code is public, never your diary pages.
2. On the new repo page, click **uploading an existing file**. Drag in **everything inside this folder**, all the files, then click **Commit changes**.
3. Go to **Settings → Pages**. Under *Branch*, choose `main` and `/ (root)`, then click **Save**.
4. Wait about a minute. Your app will be at `https://YOUR-USERNAME.github.io/little-diary/`

## Keep your pages safe

Your pages live only on the phone you write on. In the app, open **themes → download backup** every now and then. On a new phone, use **restore backup** to bring everything back.

Deleting the app from the home screen, or clearing Safari/Chrome website data, deletes your pages too. Download a backup first.

## Updating the app

Upload the new `index.html` to the repo. If you change anything else, also change `little-diary-v1` in `sw.js` to `v2`, so phones pick up the new version.
