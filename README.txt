# ML Monument PWA v3

## What changed
- Added Monument / Mausoleum job type toggle
- Saved Jobs tab with open, delete one, delete all
- CSV export for Excel
- JSON backup import/export
- Optional local photos (up to 3 per job)
- Airtable-ready sync via `config.js`

## To turn on Airtable sync
1. Open `config.js`
2. Change `enabled` to `true`
3. Paste your Airtable `baseId`, `tableName`, and `personalAccessToken`
4. Make sure your Airtable field names match the values in `fields`
5. Host the app over HTTPS

## Notes
- Photos are saved in the app and JSON backup, not in the CSV export.
- Direct photo upload to Airtable is not wired in this version.
- If Airtable is not configured, the app still works with local saved jobs.
