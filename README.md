# Meowney: install on your Android phone

This folder is your app. It works with no sign-in and no internet once installed.
Your entries, bills and settings are stored only on your phone. Nothing is sent anywhere.

## Part 1: Put the app on a free web address (about 10 minutes, on a computer)

You need a computer for this part, because uploading folders is awkward on a phone.

1. Unzip this file. You should see: index.html, manifest.webmanifest, sw.js, and the folders icons and fonts.
2. Go to github.com and create a free account (or sign in).
3. Click the + at the top right, then New repository.
   - Repository name: anything you like, for example meowney (it becomes part of the web address)
   - Choose Public (free web hosting needs this).
   - Click Create repository.
4. On the new empty page, click the link that says "uploading an existing file".
5. Drag in everything from the unzipped folder: index.html, manifest.webmanifest, sw.js, the icons folder and the fonts folder.
   Wait until every file has finished uploading, then click Commit changes.
6. Click Settings (top of the repository), then Pages (left side).
   - Under Build and deployment, set Source to "Deploy from a branch".
   - Branch: main, folder: / (root). Click Save.
7. Wait 1 to 3 minutes and refresh that page. A web address appears at the top, like:
   https://YOUR-USERNAME.github.io/YOUR-REPOSITORY-NAME/
8. Open that address on your phone to check it loads.

The files are public at that address, but they contain no personal data. Your entries never leave your phone.
GitHub's screens change now and then, so button names may differ a little.

## Part 2: Install it on your phone

1. Open the address in Chrome on your Android phone.
2. Tap the three dots menu, then "Install app" (or "Add to Home screen").
3. Open Meowney from your home screen. It now works offline.

## Part 3 (optional): Make a real APK file

Only do this if you specifically want an APK. Installing from Chrome (Part 2) is simpler and works the same.

1. On a computer, go to pwabuilder.com and paste your web address from Part 1. Click Start.
2. Click "Package for stores", then choose Android and generate the package.
3. Leave the signing key on "New". PWABuilder makes one and puts it in the download.
   Keep that key file somewhere safe. You need it for future updates.
4. Download the package, unzip it, and find the .apk file.
5. Send the APK to your phone. Android will ask you to allow installs from this source (Settings, then "Install unknown apps" for the app you opened it with). It may also show a security warning, because the app isn't from the Play Store.

I'm not sure whether an APK install and the Chrome install share the same data, so choose one and use only that.

## Keep your data safe

- Your data lives only on this phone. If you uninstall the app, clear its data, or lose the phone, it is gone.
- In the app, open Settings and tap "Back up everything". It saves one file with your entries, settings and bills.
- Save that file somewhere safe (Google Drive, email it to yourself). Do this about once a month.
- To move to a new phone, or to recover, install the app there and use "Restore from backup".
- You can also move your data from the Claude-hosted version: use its "Back up everything", then restore the file in this app. Bills from that version don't come across.

## Updating the app later

Replace the files in your GitHub repository with new ones (Add file, then Upload files). Open the app while online and it updates itself. Your data is not touched.

## The cat and its greetings

Every time you open the app, the cat says something based on the time, the date and your recent entries. Tap the x to dismiss it. Pick Sassy, Sweet or Silent under Settings, then Pet reactions. Silent turns the greeting off.

## What is different from the Claude-hosted version

- No AI "Read from bill". You type bill details yourself. Photos and PDFs still attach and are stored on your phone.
- No sync between phones. Each person installs their own copy with their own data.
