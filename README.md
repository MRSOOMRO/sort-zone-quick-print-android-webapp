# Sort Zone Quick Print Android Web App

Android-friendly PWA for Sort Zone Quick Print.

## Files

Upload these files to the repo root:

- index.html
- manifest.webmanifest
- service-worker.js
- README.md

Keep these folders:

- icons/
  - icon-192.png
  - icon-512.png

- stem/
  - DCE1.csv

## GitHub Pages setup

1. Go to repository Settings
2. Open Pages
3. Select Deploy from branch
4. Select branch: main
5. Select folder: /root
6. Save

Your app will be available at:

https://mrsoomro.github.io/sort-zone-quick-print-android-webapp/

## Android install

1. Open the GitHub Pages link in Chrome
2. Tap the three dots
3. Tap Add to Home screen or Install app
4. Open from the phone home screen

## STEM data

The app loads DCE1 STEM from:

./stem/DCE1.csv

Do not add the CSV to service-worker cache because it may be large.

## Version

v23
