# Sort Zone Quick Print PWA

iPhone friendly PWA for label preview.

## What works

- Quick Print UI
- STEM CSV import
- Label QR preview
- Active clusters A to Z
- Aisle ranges
- Bag locations by cluster
- Add to Home Screen support
- Offline shell caching after first load

## iPhone install steps

1. Host these files online.
2. Open the link in Safari.
3. Tap Share.
4. Tap Add to Home Screen.
5. Tap Add.

## GitHub Pages hosting

Upload these files to a GitHub repo.

Go to Settings > Pages.

Choose branch main and root folder.

Share the Pages URL with users.

## Printing

This PWA is preview only for now.

Direct Zebra printing can be added later through:
- Native iOS app
- Local print server
- Backend print API


## v1.1 changes

- Added visible Import STEM button in the top bar.
- Added visible Setup button in the top bar.
- Added Import STEM and Setup toolbar on the Quick Print screen.

## v1.2 changes

- Fixed iPhone Home Screen safe-area overlap.
- App now uses 100dvh for installed PWA view.
- Bottom controls no longer cover content.
- Cluster, aisle, and label screens fit better on iPhone.
- Preview popup stays inside the visible screen.
- Service worker cache updated to v12.

## v1.3 rebuilt changes

- Removed hidden bottom footer.
- Added permanent Setup and Import buttons in the header.
- Fixed iPhone installed PWA bottom overlap.
- Cluster grid now fits cleaner in the visible screen.
- Search row remains visible without being covered.
- Aisle and label screens have safer bottom spacing.
- Service worker cache updated to v13.

## v1.4 changes

- Preview popup now displays the actual Resource ID.
- Replaced generic "Resource ID found" text.
- Service worker cache updated to v14.

## v1.5 changes

- Forced popup subtitle to show the actual Resource ID.
- Added runtime override to prevent old Resource ID found text.
- Service worker cache updated to v15.

## v1.6 changes

- Fixed Resource ID lookup.
- STEM total count is now kept separate from each label Resource ID.
- Preview popup shows the actual Resource ID value from CSV.
- QR is generated from the actual Resource ID, not the STEM count.
- Service worker cache updated to v16.
