# Profile website — Nguyen Thanh Tu

Static personal profile site, hosted on GitHub Pages (`https://shicukoe.github.io`). Also the demo
target repo for the AutoPilot AI agent.

- `index.html` — all content (hero, experience, projects, skills, education, certifications). Plain HTML,
  no build step.
- `style.css` — all styling. One dark synthwave theme: neon cyan/blue with hot-pink accents, a striped retro
  sun behind the photo, and a scrolling neon grid under the hero. Colors are CSS variables on `:root`; reuse
  them instead of hard-coding new colors. Animations must stop under `prefers-reduced-motion`.
- `img/` — images. Keep them small (the profile photo is ~50 KB).
- No JavaScript, no framework, no dependencies besides the Orbitron font from Google Fonts. Keep it that way
  unless a task explicitly asks.
- Content is in English, short plain sentences, one idea per bullet.
- Must stay readable at phone width (16px side padding, no horizontal scroll).
