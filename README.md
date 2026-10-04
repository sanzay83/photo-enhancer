# Photo Enhancer

A client-side photo editing web app. Single self-contained `index.html` — no
build step, no server, no sign-up. Open it in a browser and start editing.

## Features

- **Compact icon-bar UI** — every adjustment lives behind an icon; tap one and
  its slider pops up right above the bar.
- **Shadow & highlight recovery** — pull detail out of dark areas and tame
  blown-out brights without shifting overall exposure.
- **Color tone balance** — automatically detects an over-dominant color
  channel (e.g. excessive red), pulls it down, and gently lifts the others.
- **Auto-select by sharpness** — one tap finds the sharp, in-focus subject;
  refine the selection with Add/Erase brushes directly on the image.
- **Independent front object / background adjustment** — tune the subject and
  the background separately (color, warmth, brightness, smoothness, detail).
- **Batch mode** — shared settings across photos, with per-image override so
  any photo can break away with its own tweaks.
- **Metadata preservation** — exports keep the original EXIF (camera info,
  capture date, GPS, captions, copyright) by default, with a toggle to strip
  it instead.

Built with Muse.
