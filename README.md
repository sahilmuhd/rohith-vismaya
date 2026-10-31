# Rohith & Vismaya — Wedding Invitation

Static site (HTML/CSS/JS + GSAP). Cloned from the Drishya & Hardeep reference and personalised.
Deploy by uploading this whole folder to GitHub Pages, Netlify, Vercel or Hostinger (`index.html` at the root).

## Before you publish — 4 things to fill in
1. **Social-share URLs** — already set to https://rohith-vismaya.vercel.app/ (change them in the `<head>` of `index.html` if the domain changes).
2. **Verified map links** — near `MAP_URLS` in the script, paste the exact Google Maps share link for each venue. Until then the "Directions" buttons open a Google Maps *search* by venue name (no coordinates were invented). Please check the embedded maps show the right places.
3. **RSVP** — the section is commented out in `index.html` (search "RSVP section temporarily disabled"). Re-enable it with `RSVP_SETUP.md` when ready.
4. **Music** — add your own licensed instrumental as `music/song.mp3`. No music is bundled.

## Media
- `media/opening-landscape.mp4` / `opening-portrait.mp4` — opening (from IMG_9887); the page picks by screen orientation. The portrait cut is the same footage on a blurred fill (no stretching/cropping of faces).
- `media/clip-1.mp4`, `clip-2.mp4` — cinematic section (from IMG_0959). Both are H.264, muted, ~1–4 MB, lazy-loaded, paused off-screen, with posters and a pause/play button.
- `gallery/01–08.jpg` — all 8 photos (lightbox with arrows, keys and swipe).

## Notes
- Countdown target: 13 Dec 2026 10:00 AM IST; shows a thank-you message afterwards.
- Spelling "Kodakkkad" is kept exactly as supplied — please confirm.
- GSAP (cdnjs) and Lenis (unpkg) load from CDN as in the reference.
- Reduced-motion preference is respected (no autoplay video, no smooth-scroll/animations).
