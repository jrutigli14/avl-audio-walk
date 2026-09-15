# AVL Audio Walk

A lightweight GPS-aware walking guide for iPhone/Safari, tailored to start and end near Asheville's Flat Iron Building.

## What it does
- Watches iPhone GPS while the page remains open.
- Shows distance to each upcoming stop.
- Automatically narrates a stop when you come within ~95 meters.
- Uses iPhone/Safari speech synthesis, so no audio files are required.
- Provides an Apple Maps walking link for every stop.
- Saves progress on-device.
- Works offline after first load if deployed as a PWA.

## Important iPhone limitation
iOS may suspend location and speech when Safari or a home-screen web app is in the background or the phone is locked. Keep the guide open in the foreground for reliable automatic triggering.

## Best deployment
Host these files on any HTTPS static host (GitHub Pages, Netlify, Cloudflare Pages, etc.). HTTPS is required for normal browser geolocation.

## Route
16 curated Urban Trail highlights, starting at official Stop #8 (Flat Iron Architecture), looping through downtown and returning near the Flat Iron.

Pages deployment trigger.
