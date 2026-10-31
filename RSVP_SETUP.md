# RSVP setup (new endpoint required)
The old project's endpoint has been removed. To enable RSVPs:
1. Create a new Google Sheet. Extensions → Apps Script → paste `google-apps-script.js` → Save.
2. Deploy → New deployment → Web app → Execute as *Me*, access *Anyone* → copy the URL.
3. In `index.html` set `const RSVP_ENDPOINT = "<your URL>";` (search for `RSVP_ENDPOINT`).
Fields sent: name, phone, guests, attending, message. Until step 3, the form is disabled and shows the family contact number instead.
