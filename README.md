# Emoji Rain ☔✨

A playful interactive canvas demo where emojis fall like rain and stack into piles at the bottom of the screen. Click or tap anywhere for a burst of emojis — press **Space** for an overhead shower.

## Features

- **Continuous emoji rain** — emojis fall from the top and settle in a pile near the bottom
- **Click / tap burst** — spawns a fountain of emojis at the cursor position
- **Space key** — triggers a rain burst from above
- **Smart stacking** — emojis pile up but never obscure the centered welcome text
- **Responsive** — scales to any screen size
- **Emoji variety** — 90+ emojis across 8 Unicode categories

## How it works

An HTML Canvas particle system with simple gravity physics. Each emoji drifts sideways (simulated wind), rotates as it falls, and settles onto a pile grid that tracks the surface height in columns. A cap prevents the pile from reaching the text zone.

## Deploy

Hosted on **GitHub Pages**: [https://dazu-ryomaid.github.io/emoji-rain/](https://dazu-ryomaid.github.io/emoji-rain/)
