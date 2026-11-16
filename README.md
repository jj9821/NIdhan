# For Ridhu — Happy 22nd Birthday ✨

A single-file, mobile-first interactive digital birthday letter experience titled **"For Ridhu — Happy 22nd Birthday"**.

---

## 🌹 Features

- **Tactile 3D Opening Envelope:** Deep espresso envelope sealed with an embossed crimson-gold wax stamp (`"22"`). Tapping the seal triggers a golden particle burst, cracks the seal, starts the music fade-in, and unfolds the envelope flap in 3D.
- **Atmospheric Palette & Architectural Motifs:** Twilight espresso (`#14100e`) and warm cream parchment (`#fbf7f0`) with subtle architectural blueprint grid lines, corner drafting tick marks (`+`), and technical spec annotations honoring her as an architect.
- **Ambient Golden Dust:** Full-screen HTML5 `<canvas>` rendering slow, undulating golden starlight dust motes.
- **Line-by-Line Ink Writing Engine:** Parses the letter into individual visual lines and sentences while preserving all paragraph breaks and blank spacing:
  - Smooth left-to-right calligraphy wipe with a glowing golden fountain pen nib indicator.
  - Realistic emotional pacing: proportional line duration, 400ms natural breath pause after sentences, and 950ms reflective pause after paragraphs.
  - Smart auto-scroll with manual scroll detection and a `"↓ Follow ink"` recovery pill.
  - Discreet floating controls: speed toggle (`1x`, `1.5x`, `2x`), pause/resume (`⏸`/`▶`), and `⚡ Instant Read`.
- **Grand Finale Keepsake Moment:** After the final signature (*"Always with love, never with expectations. ❤️"*), a keepsake card reveals an interactive `"Make a wish for 22 ✨"` button that launches a full-screen starlight burst across the display.

---

## 🎵 Music Setup
Place your background music file named `bg-music.mp3` in the same directory as `index.html`. The letter will automatically ramp volume up smoothly upon opening.

---

## 🚀 Live Demo & Hosting
To view locally:
```bash
python3 -m http.server 8000
```
Then visit `http://localhost:8000`.

To publish online, enable **GitHub Pages** under `Repository Settings -> Pages -> Deploy from a branch (main)`.
