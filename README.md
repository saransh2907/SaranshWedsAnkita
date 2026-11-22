# Saransh & Ankita — Wedding Invitation

A static, responsive, single-page wedding invitation website. No build tools or server are required.

## Preview locally
1. Extract the ZIP.
2. Open `index.html` in a modern browser (Chrome, Edge, Firefox, Safari).
3. For the best clipboard and map experience, run a local static server:
   - Python: `python -m http.server 8000`
   - Then open `http://localhost:8000`

## Deploy to Netlify
1. Open https://app.netlify.com/drop
2. Drag the extracted folder (the folder containing `index.html`) onto the page.
3. Netlify will publish the site and provide a shareable URL.

## Deploy to GitHub Pages
1. Create a GitHub repository and upload `index.html` and this README.
2. In repository Settings → Pages, select the branch and root folder.
3. Save and wait for GitHub Pages to publish.

## Personalization notes
- Wedding date: 12 December 2026.
- The countdown targets midnight at the start of the wedding date because no ceremony time was provided.
- Google Calendar creates an all-day event for 12 December 2026 for the same reason.
- Venue links use the Kachnar Club & Resort listing in Vijay Nagar, Jabalpur.
- Fonts load from Google Fonts; if offline, browser fallback fonts are used.

## Added interactive features
- Our Story timeline (generic copy; personalize with real milestones if desired)
- Click-to-expand photo gallery (currently illustrative stock photos; replace with the couple's own photos)
- RSVP form that prepares a WhatsApp message for the guest to send to the family
- Blessing message sharing via WhatsApp
- Native invitation sharing (or copy-link fallback)

## Important limitations / final personalization
- RSVP responses are not stored in a database. Guests choose a WhatsApp recipient and send the prepared response. For direct delivery, add a confirmed family WhatsApp number or connect a form backend.
- Gallery photos are placeholders and should be replaced with approved couple photos.
- Background music: the supplied `Raatan Lambiyan` MP3 is bundled in `assets/raataan-lambiyan.mp3`. It attempts to start when a guest taps “Open Invitation”; the fixed music control lets guests play or pause it at any time. If the browser blocks playback, guests can tap the Play button.
- The event time was not supplied, so countdown and calendar entry remain date-based/all-day.

## Music note
The music file is included as supplied. Confirm you have the necessary rights or permissions to publish and share the recording with the invitation.
