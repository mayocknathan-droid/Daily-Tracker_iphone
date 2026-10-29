# Winter Bulk Tracker: iPhone Home Screen app

The app runs fully on your phone and works offline. Your logs are saved on the phone, so tap Back up now and then and keep the file in Files or iCloud Drive.

## 1. Put it online (free, one time)

The files need a web address that starts with https. GitHub Pages is free:

1. Sign in at github.com and create a new public repository, for example `bulk`.
2. Choose "uploading an existing file" and drag in everything in this folder: `index.html`, `manifest.webmanifest`, `sw.js` and the `icons` folder. Commit.
3. Go to Settings, then Pages. Under "Branch" pick `main` and `/ (root)`, then Save.
4. After a minute your app is at `https://<your-username>.github.io/bulk/`.

## 2. Add it to your iPhone

1. Open that address in Safari.
2. Tap the Share button, then "Add to Home Screen", then Add.
3. Open it from the new "Bulk" icon. It runs full screen, like any app.

## 3. Bring your logs across from claude.ai

1. In the claude.ai version, scroll to the bottom of any tab and tap Back up. Save the file.
2. In the Home Screen app, tap Restore and pick that file.

## Updating later

Upload the new `index.html` to the same repository, change `winter-bulk-v1` in `sw.js` to `winter-bulk-v2` (and so on) and upload that too. Close and reopen the app twice to load the new version.

## What is different from the claude.ai version

- No account sync: data stays on this phone. Use Back up and Restore to move it.
- No "Describe" food estimates, which need Claude. Search (about 2,950 foods) and Create still work.
- Food values: UK food database from McCance and Widdowson's Composition of Foods Integrated Dataset 2021 (Public Health England), Open Government Licence v3.0.
