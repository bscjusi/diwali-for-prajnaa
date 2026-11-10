# Diwali gift page for Prajnaa — from Sushil — v2, multi-step

Upload the WHOLE folder — `index.html` + `images/` — no build step, no external files needed.
Sound is made in the browser (Web Audio), so it works on GitHub Pages with no audio files.

## Who it's for
Prajnaa — @prajnaa.mee on Instagram, 🇳🇵 प्रज्ञा
Khuma Bhattarai was only the sender in the example link Sushil shared — NOT the girl.

## The journey — one screen leads to the next, like the original link
1. **Envelope** — "For Prajnaa" — tap 💌 to open, with a chime
2. **Lights** — tap each diya to light it (Joy / Peace / Love / Luck / Hope), with pop sounds. Light all 5 and the string lights turn on, then Next unlocks
3. **Fireworks** — tap the sky for fireworks, with boom + crackle sounds. Big launch button too
4. **Her moments** — a photo slideshow of her own Instagram photos, with a link back to each post:
   - Dashain, her close-up, Phewa Taal Pokhara, Texas summer, San Antonio
   - Photos are in `images/` — they are her public Instagram photos, used only in this gift for her
5. **Gift card** — "Happy Diwali, Prajnaa" message, signed — Sushil, with a replay button

Sound toggle top-right. Mobile-friendly — she'll most likely open it on her phone. Tap anywhere on the final screen for a last firework.

## To personalize before sending
Edit `index.html` — the message is in Scene 5, in the `<div class="card">`.
Keep it in your own words; what's there now is warm and light, not a heavy confession.

## To host on GitHub Pages (free, ~2 minutes)
1. GitHub → New repository, e.g. `diwali-for-prajnaa` (Public)
2. Upload the WHOLE folder: `index.html` AND the `images/` folder with all 5 photos (Add file → Upload files → Commit — drag the folder in)
3. Settings → Pages → Source: Deploy from a branch → Branch: `main`, folder `/ (root)` → Save
4. Wait ~1 minute. Your link will be `https://<your-github-username>.github.io/diwali-for-prajnaa/`
5. Send her that link — e.g. "Made you something for Diwali 🪔 turn your sound on" + the link

Important: if you upload only index.html, the photos won't show. Upload images/ too.

## Timing
Diwali 2026 was Nov 8 — sending Nov 9–10 still lands inside the festival week.
Don't sit on it past then; the moment fades fast.

## v3 — cinematic, like the original
- Dark intro: glowing orb + "Sushil Presents" — tap to begin, auto-continues after ~3s
- Rangoli reveal: lighting all 5 diyas reveals a colourful rangoli
- Lanterns: paper lanterns rise in the fireworks and finale scenes
- Particle text finale: "Happy Diwali / from Sushil" forms in sparkling dots, like the original

## GitHub version
This repo copy is self-contained: the 5 photos are embedded in index.html as base64, so GitHub Pages serves the page from index.html alone. No images/ folder is needed in the repo.
