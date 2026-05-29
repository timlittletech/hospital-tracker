# Hospital Tracker

A tiny single-file web app for tracking a hospital stay — pain levels, medications, bowel activity (relevant post-bowel-resection), questions for the medical team, care received, and freeform notes.

Built for Tim's small bowel resection stay, May 2026.

## Use

Open the app on your phone (Pages URL — see repo settings). Tap a quick-add button, fill in the form, save. Timeline view shows everything chronologically with filter chips by type.

- **Data lives in your browser's localStorage.** Clearing browser data wipes the log.
- **Export** button downloads a JSON backup. Do this periodically — email it to yourself.
- **Import** restores from a JSON backup if you switch devices or lose data.
- **Stay start** sets the arrival timestamp so the header shows "Day 2 (4h in)" style context.

## Add to home screen

For an app-like experience on iPhone: Safari → Share → Add to Home Screen. The app is set up with the right meta tags to launch fullscreen.

## Stack

- Vanilla HTML / CSS / JS — no build step, no framework, no dependencies
- localStorage for persistence
- Mobile-first dark theme

## Privacy

Data never leaves the browser. No analytics, no telemetry, no backend. The hosted site (GitHub Pages) only serves the static HTML.

## License

Personal use. No license granted for redistribution.
