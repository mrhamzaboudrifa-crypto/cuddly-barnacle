APP-STYLE PLUMBING WEBSITE (2026 look)

This is a static "app-like" site:
- Circular service icons with symbols
- Tap service -> detail page (price, deposit, booking)
- Optional PWA (Add to Home Screen) + offline shell

DIARY / AVAILABILITY:
GitHub Pages is static hosting (no backend). A real "login diary" + payments needs a backend.
The practical way:
- Use Square Appointments / Calendly / similar to handle diary + deposits
- You log in there and set hours; customers see only available slots
- This site links to (or can embed) that booking page

EDIT:
Open index.html and edit:
- CONFIG.whatsappNumber (e.g. 447123456789)
- CONFIG.bookingLink
- CONFIG.bookingEmbedUrl (optional)
- SERVICES prices and deposits

UPLOAD:
Upload ALL files into repo root:
- index.html
- manifest.json
- sw.js
- icon.svg
Then Settings -> Pages -> main / root.
