# 🎂 Happy Birthday, Harrison Oppong!

An animated, interactive birthday page built with vanilla HTML/CSS/JS plus a few
open-source libraries loaded via CDN:

- [GSAP](https://gsap.com/) — scroll and entrance animations
- [canvas-confetti](https://github.com/catdad/canvas-confetti) — confetti cannons
- [fireworks-js](https://github.com/crashmax-dev/fireworks-js) — fireworks show
- [tsParticles confetti](https://particles.js.org/) — extra particle bursts
- [Font Awesome 6](https://fontawesome.com/) — dynamic icon for the achievement card

## Features

- Animated gradient name reveal, letter by letter
- Twinkling starfield background
- Floating balloons and emoji you can click/pop
- "Make a Wish" button — golden flash, toast message, ribbon streamers
- "Surprise Me!" button — fireworks + confetti cannon combo
- Media gallery with lightbox for photos/videos
- Background music toggle

## Adding your own media

The gallery and music expect these files to sit next to `index.html`:

- `birthday-song.mp3`
- `photo_2026-07-11_19-04-52.jpg`, `photo_2026-07-11_19-04-56.jpg`
- `video_2026-07-11_19-04-29.mp4`, `video_2026-07-11_19-04-43.mp4`, `video_2026-07-11_19-04-47.mp4`

(Or edit the `mediaData` array near the bottom of `index.html` to point at your own filenames.)

## Running locally

Just open `index.html` in a browser — no build step required.

## Hosting

This is a static site, so it works great on GitHub Pages, Netlify, Vercel, or any
static host. For GitHub Pages: Settings → Pages → Deploy from branch → `main` → `/ (root)`.
