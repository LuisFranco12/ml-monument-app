MONUMENT MEASURE — iPHONE / PWA VERSION

This package is ready to be hosted as a small website and then added to an iPhone Home Screen.

FILES
- index.html — the Monument Measure app
- manifest.webmanifest — tells the phone how the installed web app should behave
- service-worker.js — caches the app so it can continue opening offline after it has been loaded
- README.txt — this guide

RECOMMENDED INSTALL FLOW
1. Host these files together on an HTTPS website.
2. Open the website URL in Safari on the iPhone.
3. Tap Safari's Share button.
4. Tap "Add to Home Screen".
5. Name it Monument Measure and tap Add.
6. Launch it from the new Home Screen icon.

IMPORTANT DATA NOTE
Measurements/accounts are stored locally in the browser/app storage on that device.
Use the built-in Backup Data (.json) option regularly and export the final Excel workbook.
Deleting Safari website data or removing certain stored website data can erase local app data.

OFFLINE
After the hosted app has successfully loaded and its offline cache is installed, it is designed
to reopen without an internet connection. Excel export is generated on-device and does not
require a server.

This PWA is based on Monument Measure v7:
- searchable large account list
- Delete All Accounts
- account insertion order preserved
- blank new measurement fields
- one-row-per-account Excel export
- headstones first, then flats, then slants
- Standard ML and $155/$195 pricing
- color coding and formatted prices
