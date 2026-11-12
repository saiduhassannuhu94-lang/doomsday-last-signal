# DOOMSDAY // LAST SIGNAL

A mobile-first, fictional sci-fi horror countdown experience built with plain HTML, CSS and JavaScript.

## Features
- Cinematic opening transmission and horror-style visual effects
- Absolute-time countdown to **13 November 2026, 23:59 Africa/Lagos**
- Watcher Protocol message rotation
- Alien frequency decoder
- Humanity's Last Vote (local browser storage)
- Last Wish Wall (local browser storage)
- Escape attempt and emergency override interactions
- Optional synthesized ambient sound, off by default
- Installable PWA manifest and lightweight offline app shell
- Reduced-motion support and responsive mobile layout

## Run locally
Open `index.html` in a browser. For service-worker/PWA testing, serve the folder over localhost or HTTPS.

## Deploy to Vercel
1. Import this GitHub repository into Vercel.
2. Choose **Other** as the framework preset if prompted.
3. Leave Build Command and Output Directory empty/default for a static site.
4. Deploy.

## Important scope notes
This first release is a static client-side experience. Votes and wishes are stored in the visitor's browser and are **not shared** between visitors. A Supabase backend is required for shared posts, moderation, reporting and global vote totals.

The countdown is a fictional story prop, not a prediction or emergency alert. The site does not access visitors' camera, microphone, GPS or contacts. Browser background execution and audio can be suspended by mobile operating systems; the countdown recalculates from its fixed timestamp when the page resumes.

## License
MIT