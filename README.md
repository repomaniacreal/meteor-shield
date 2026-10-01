# Meteor Shield

A neon arcade defense game in a single HTML file. No build step, no dependencies — just open `index.html` in a mobile or desktop browser.

## How to play

- **Rotate your shield** with the on-screen ◀ ▶ buttons, by holding the left/right side of the screen, or with the arrow keys on desktop.
- **Block every meteor** hurtling toward your planet. Blocked meteors explode for points and build your combo.
- **Golden meteors** trigger a shockwave that destroys every meteor on screen — huge bonus!
- **Don't let meteors through**: each one that hits your planet costs a life. You have 3 (up to 5).
- **Level up** every 20 blocks — meteors get faster and more frequent.
- **Extra life** every 2,500 points.

## Features

- Combo scoring with rising pitch feedback
- Shockwave bonus meteors
- Particles, screen shake, hit flash, glow effects, generated sound effects (no audio files)
- Pause button, auto-pause when tab hidden
- Persistent best score via localStorage
- Mobile-first portrait layout, works offline

## Run locally

Just open `index.html` — or serve the folder with any static server:

```bash
npx serve .
```

## Deploy

Deploys as a static site anywhere (Vercel, Netlify, GitHub Pages).
