# Tihar gift page for Prajna — v13

A single `index.html` — photos are embedded in the file, music streams from Archive.org. No build step.

## Music — v13 (2026-11-09, your feedback)
- **Deusi Bhailo Instrumental** — the Tihar song, not Malshree Dhun (that was a Dashain song).
- Flute / guitar / madal, 4:14, from Archive.org (`DeusiBhailoInstrumental_201710`), plain MP3, no ads, no YouTube.
- Plays softly in the background throughout, starting on the first tap (volume 0.12, ducks to 0.02 on firework booms). The sound toggle pauses/resumes it.

## Changes in v12 (phone fix, 2026-11-09)
- Fixed taps doing nothing on phone: the audio element was after the script and crashed it before any tap handler was attached. Audio now sits before the script, with null guards, and tapping anywhere on the envelope scene opens it.

## Changes in v10 (2026-11-09)
- YouTube removed entirely — the ads came from the YouTube embed. Music is now a plain MP3 from Archive.org.

## Changes in v4 (2026-11-09, your feedback)
- Says **Happy Tihar**, not Happy Diwali — in Nepal we say Tihar. Name is **Prajna** (no Devanagari, no "Prajnaa").
- No Instagram links anywhere, and no Instagram handle.
- Only **two photos**: Dashain and the close-up smile.

## The journey — one screen leads to the next, like the original link
1. **Envelope** — "For Prajna" — tap anywhere to open, with a chime
2. **Lights** — tap each diya to light it (Joy / Peace / Love / Luck / Hope), with pop sounds. Light all 5 and the string lights turn on, the rangoli is revealed, then Next unlocks
3. **Fireworks** — tap the sky for fireworks, with boom + crackle sounds. Big launch button too
4. **Her moments** — a photo slideshow of just two photos: Dashain, and her close-up smile
5. **Gift card** — "Happy Tihar, Prajna" message, unsigned, with a replay button. Particle text "Happy Tihar / for Prajna" forms in sparkling dots.

Sound toggle top-right (also turns the Deusi Bhailo on/off). Mobile-friendly — she'll most likely open it on her phone.

## Hosting
GitHub Pages, repo `bscjusi/diwali-for-prajnaa`, branch `main` / root.
Link: https://bscjusi.github.io/diwali-for-prajnaa/ — also https://is.gd/happytiharprajna

## Timing
Tihar / Diwali 2026 was Nov 8 — sending Nov 9–10 still lands inside the festival week.
