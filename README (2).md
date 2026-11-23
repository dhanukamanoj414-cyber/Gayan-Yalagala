# Personal Finance Manager — iPhone PWA

Mobile-first installable Progressive Web App. It keeps the desktop app's LKR income and expense categories and provides dashboard summaries, transaction CRUD/search/filter/sort, bar and pie charts, pie-category transaction drill-down, monthly/yearly reports, budgets with 80% warnings and exceeded alerts, savings target, custom categories, CSV export and JSON backup/restore.

## Publish and install on iPhone
A PWA must be hosted on an HTTPS website for service-worker/offline support. This ZIP is the website source, not an installable iOS binary.

1. Upload the contents of this folder to a static HTTPS host (for example GitHub Pages, Netlify or Cloudflare Pages). Keep all files together.
2. On your iPhone, open the HTTPS address in **Safari**.
3. Tap **Share** → **Add to Home Screen** → **Add**.
4. Open the new Home Screen icon once while online. The service worker caches the app shell for offline use.

## Local data and privacy
Transactions, budgets and custom categories are stored in browser localStorage on this iPhone. There is no cloud sync or server upload. Use More → Back up all data (JSON) regularly. Clearing Safari website data or removing the app may erase data. The optional PIN is a convenience lock, not encryption; browser storage is not encrypted by this app. Protect the iPhone with its device passcode.

## Notes
- No automatic sync with the desktop version. To move data, export JSON from one installation and restore it in the other.
- Reports can be printed or saved as PDF through the iOS print/share sheet.
