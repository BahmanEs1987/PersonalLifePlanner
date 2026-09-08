# Personal Life Planner V1

Life Planner / Life Archive PWA, Persian-first and offline-first.

## V1 highlights
- Real Jalali/Persian calendar with Gregorian date shown smaller in each day cell.
- Jalali month length and leap-year behavior derived from the browser's Persian calendar implementation rather than a hard-coded month table.
- Today, tasks, habits, events, journal, finance, search, timeline.
- Vehicle module: oil, timing belt, tires, battery, engine, gearbox, custom maintenance; mileage/date/cost/brand/notes; service costs flow into the main Vehicle expense category.
- Local IndexedDB storage.
- Normal JSON export/import.
- Encrypted backup using PBKDF2 + AES-GCM in the browser.

## Important security / cloud note
This V1 does NOT claim that GitHub Pages itself is a secure private cloud database. Data entered in the PWA is local to the browser/device. Encrypted backup can be exported and stored in a private cloud/file service.

For the long-term production version, use a real authenticated backend or native Apple architecture with private cloud storage, per-user encryption, sync conflict handling, version history, recovery, and passkeys/biometrics. Do not put API secrets in this repository.

## GitHub Pages
Upload all files at repository root and keep the `icons` folder intact. Enable Pages from `main` / root.
