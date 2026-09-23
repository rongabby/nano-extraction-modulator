# NEMOD – Nano Extraction Modulator

Open-source **frequency wellness station** (Web Audio). Play pure tones with optional masking audio. No medical claims are made — use at your own discretion.

## Live URL

**https://rongabby.github.io/nano-extraction-modulator/**

(Also deploys from this repo’s `main` branch as a static site.)

## How to use

1. Open the live page (or open `index.html` locally).
2. Pick a preset (nano-extraction or solfeggio) or drag the frequency slider.
3. Adjust **Tone Volume** and optional **Masking Track Volume**.
4. Press **START / STOP** (or **AUTO-LOOP** for a 20‑minute cycle through nano presets).
5. Optional: upload a local masking track (MP3/WAV), **or** open a radio drawer:

### Calm Radio & Rock U drawers

- **Calm Radio** and **Rock U** buttons (and sticky side tabs on desktop) open a slide-over panel so you can listen while NEMOD tones run.
- **Rock U** embeds [rockuunderstanding.online](https://www.rockuunderstanding.online/) with a tab for [Cosmic Radio](https://www.rockuunderstanding.online/radio). Use Rock U’s own volume slider to duck under the NEMOD tone.
- **Calm Radio** tries to embed [calmradio.com](https://www.calmradio.com/). If the site blocks framing (common), the panel shows a clean **Open Calm Radio here** button (new tab) plus a tip to balance volumes with NEMOD’s Tone Volume.
- Close with the × button, backdrop click, or **Escape**. Only one drawer opens at a time.
- Browser autoplay / iframe policies may require a click inside the drawer before radio audio starts.
- Local masking file upload remains available and does not conflict with the drawers.

## Files

| File | Role |
|------|------|
| `index.html` | Canonical NEMOD page (tones + drawers) |
| `!DOCTYPE-nano-extractor.html` | Legacy redirect → `index.html` |

## Develop locally

```bash
# any static server, e.g.
python3 -m http.server 8080
# then open http://localhost:8080/
```

## License / notes

Personal wellness experiment tool. Soft wellness language only — no medical claims.
