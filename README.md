# Meowney

A small, private money tracker for your phone, with a pet that reacts to what you spend.

**Open it here:** https://saiteja-j.github.io/meowney/

No account. No server. No ads. Your entries live **only on your phone**, so make a backup now and then (see below).

## Install on Android

1. Open the link above in Chrome.
2. Tap the three dots, then **Install app** (or **Add to Home screen**).
3. Open Meowney from your home screen. A short tour starts the first time.

It works offline once opened.

## What you can do

- **Add an entry in seconds:** amount, category, account, note, tags, bill photos, repeat.
- **Home:** this month's spending against your budget, how it compares with the same days last month, and a ring showing where the money went. Your pet greets you when you open the app and peeks over the card to talk. Tap the pet for another note.
- **Entries:** browse by month, search, bulk edit, trash with undo. The pet and a one-line note sit in the month card.
- **Budgets:** one monthly number and optional category budgets. The pet rides each progress bar and reacts to your pace.
- **Insights:** a scorecard you choose (4 of 9), spending by category with month-by-month detail, fixed vs flexible, day of week, "was it worth it", and a weekly pet recap you can replay.
- **Pets:** cat, panda, penguin or puppy. Pick one or several (a different one greets you each time). Choose a personality: sassy, sweet, funny, bossy, mixed, or silent.
- **CSV:** import bank statements, export your entries for a spreadsheet.
- **Backup and restore:** one file with everything, including bill photos.
- **Light and dark mode.** Rupees by default, other currencies supported.

## Back up your data

Open **Settings, then Back up everything**. Keep the file somewhere safe (Drive, email to yourself). To restore, use **Settings, then Restore from backup**. Back up before each update.

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

Everything stays in your browser's storage on your device. Nothing is sent anywhere. Clearing the site's data or uninstalling the app erases your entries, so keep a backup.

## Credits

Icons from [Lucide](https://lucide.dev) (ISC licence). Fonts: DM Sans and Fredoka (SIL Open Font Licence). Pet illustrations were made for this project.

## Status

Built and tested in a desktop browser engine and an automated test suite. It has not been tested on every phone, so if something looks off on yours, note the screen and the phone model.
