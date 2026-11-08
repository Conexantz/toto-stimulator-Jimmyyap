# TOTO Lucky Draw

A slot-machine style TOTO number generator for Singapore Pools TOTO.

- Pick Ordinary or System 7 to System 12 entries, with the matching cost
- Numbers are weighted by all-time frequency (45%), overdue streak (35%) and pure luck (20%)
- Ordinary picks are re-rolled if odd/even, low/high and sum are all lopsided
- The header shows the next draw live (Mondays and Thursdays, 6:30pm SGT)
- "How it works" explains the maths with charts and the last 10 draws

For entertainment only. TOTO is a game of chance and no algorithm can predict results.
National Problem Gambling Helpline: 1800-6-668-668.

## Deploy on Vercel

It is a single static page with no build step.

1. In Vercel, choose **Add New → Project** and import this repository.
2. Framework Preset: **Other**. Leave Build Command and Output Directory empty.
3. Click **Deploy**.

Every push to `main` redeploys automatically.

## Run locally

Open `index.html` in a browser, or run `npx serve .` in this folder.
