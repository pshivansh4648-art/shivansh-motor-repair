SHIVANSH MOTOR REPAIR — MOBILE WEB APP (PWA STARTER)

Files:
- index.html: app interface, Hindi/English, calculator, fault guide, personal motor records
- logo.svg: app logo
- manifest.webmanifest and sw.js: install/offline support for supported browsers

How to use on a OnePlus phone:
1. Upload the entire folder to a static HTTPS hosting service (for example, GitHub Pages or Netlify). The app needs a web address for install/offline PWA features.
2. Open that HTTPS address in Chrome on the OnePlus.
3. Open Chrome menu (three dots) > "Add to Home screen" or "Install app" if offered.
4. Open from the new home-screen icon.
5. Add motor details and tap Save Record.

Important:
- Data is stored in the browser's local storage on that phone. Clearing browser/app data may erase it. Use Download Backup and keep the JSON backup somewhere safe.
- This is an initial offline-capable prototype. Online automatic technical updates are NOT implemented yet; they require an online source and an update mechanism.
- Winding turns/wire size cannot be safely determined from HP alone. Verify against manufacturer data/original winding details.
- For electrical work, isolate power and follow qualified safety procedures.
