# Grade 5 Studio

Daily practice app for ABRSM Grade 5 piano (theory, sight-reading, mock tests, practical).
Static page; no data lives in this repository. Sync goes to a private Google Apps Script
endpoint configured in `config.js`, protected by a family key entered once per device.

- `index.html` — the app
- `config.js` — `G5_SYNC_URL` (the Apps Script web-app URL)
- `updates.json` — videos and notes pushed by Claude; the app reads it on load
