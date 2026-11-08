# Meowney

A small, private money tracker for your phone, with a pet that reacts to what you spend.

**Open it here:** https://saiteja-j.github.io/meowney/

No account. No server. No ads. Your entries live **on your phone**, so make a backup now and then (see below). If you choose, Meowney can also keep a backup copy in your own Google Drive.

## Install on Android

1. Open the link above in Chrome.
2. Tap the three dots, then **Install app** (or **Add to Home screen**).
3. Open Meowney from your home screen. A short tour starts the first time.

It works offline once opened.

## What you can do

- **Add an entry in seconds:** a clean screen; tap the amount box for the calculator. As you type a note, earlier notes with those letters appear (any case); tap one to fill the note and category. Account, tags, bill photos and repeat sit below.
- **Home:** this month's spending against your budget, how it compares with the same days last month, and a ring showing where the money went. Your pet greets you when you open the app and peeks over the card to talk. Tap the pet for another note.
- **Entries:** browse by month, search, trash with undo. Press and hold the small icon box of an entry to select several, then change their category or tags in one go. The bar at the bottom has an X to leave selection, **Clear** to un-tick everything and **Select all**. "Sort" suggests a category for entries that need one (from notes you already sorted), and you accept, skip or undo.
- **Budgets:** one monthly number and optional category budgets. The pet rides each progress bar and reacts to your pace.
- **Insights:** a scorecard you choose (4 of 9), spending by category with month or quarter detail, fixed vs flexible, day of week, "was it worth it", more breakdowns (account, top notes, tags, income sources, part of the month, entry size) and a weekly pet recap you can replay. Tap a category, a weekday or a breakdown row to see the entries behind it.
- **Pets:** cat, panda, penguin or puppy. Pick one or several (a different one greets you each time). The cat has extra poses: waving on Home, a coin, a piggy bank and more on the scorecard, and pushing a block on Budgets bars. Choose a personality: sassy, sweet, funny, bossy, mixed, or silent.
- **CSV:** import bank statements, export your entries for a spreadsheet.
- **Backup and restore:** one file with everything, including bill photos. Optional **Google Drive backup** keeps a copy in a hidden folder of your own Drive, and restores it on a new phone.
- **Light and dark mode.** Rupees by default, other currencies supported.

## Back up your data

Open **Settings, then Back up everything**. Keep the file somewhere safe (Drive, email to yourself). To restore, use **Settings, then Restore from backup**. Back up before each update.

## Google Drive backup (optional, off by default)

Open **Settings, then Google Drive backup, then Turn on**. Meowney saves one file in a hidden folder that only Meowney can open. It cannot see your other Drive files. You will not see the file in the Drive app.

- Google ends the sign-in after about an hour and when the app restarts, so you tap **Sign in** once per session. While you are signed in, Meowney backs up a short while after you make changes.
- **New phone:** open Meowney, tap **New phone? Restore from Google Drive** on Home, and sign in with the same Google account.
- If Drive already holds a backup that did not come from this phone, Meowney asks before it replaces anything.
- Turning it off keeps the copy in Drive. To remove Meowney's access completely, use *third-party access* in your Google account.

*Export entries as CSV* is for spreadsheets only. It does not save your categories, budgets, settings or bill photos, so it is not a backup.

## Updating

This repository holds the finished app, with no build step. To update, replace the changed files and commit. After an update, open the app twice: the first open can still show the old version while the new one downloads. If the home-screen icon does not change, remove the app and install it again (back up first).

## Files

| File | What it is |
|---|---|
| `index.html` | The whole app (pictures and code are inside it) |
| `sw.js` | Lets the app work offline and pick up updates |
| `manifest.webmanifest` | Name, colours and icons for installing |
| `icon-192.png`, `icon-512.png`, `icon-maskable-512.png` | App icons |
| `dmsans.woff2`, `fredoka.woff2` | Fonts |
| `README.md` | This file |

## Privacy

Everything stays in your browser's storage on your device. Nothing is sent anywhere unless you turn on Google Drive backup. If you do, the app loads Google's sign-in script and sends your backup file to your own Google Drive, and nowhere else. Clearing the site's data or uninstalling the app erases your entries, so keep a backup.

## Credits

Icons from [Lucide](https://lucide.dev) (ISC licence). Fonts: DM Sans and Fredoka (SIL Open Font Licence). Pet illustrations were made for this project.

## Status

Built and tested in a desktop browser engine and an automated test suite. It has not been tested on every phone, so if something looks off on yours, note the screen and the phone model.
