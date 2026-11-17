# Breathing in Harmony: The Maestro

Voice-controlled conductor game for the Zuellig Pharma "Breathing in Harmony" HCP meeting (18 December 2026).
Single page: `public/index.html` (three.js, sampled orchestra and game code are all inlined).

Deploy: Cloudflare Workers static assets. `npx wrangler deploy` in this folder, or connect this repo in
Cloudflare > Workers & Pages > Create > Import a repository (deploy command `npx wrangler deploy`).
The microphone only works over HTTPS.

Credits
- Music: W.A. Mozart (Eine kleine Nachtmusik), J. Pachelbel (Canon in D), L. van Beethoven (Ode to Joy), public domain, arranged for this game.
- Instrument samples: FluidR3 GM soundfont by Frank Wen via gleitz/midi-js-soundfonts, CC BY 3.0.
- 3D engine: three.js r147, MIT License.
