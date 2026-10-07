# Rectified Language Flow — project page

Live at **https://rectifiedflow.github.io/ReLF/**

A static page, served by GitHub Pages from the root of `main` (`.nojekyll` turns off Jekyll):

- `index.html`: the whole page. The replay data (ReLF trajectories and the AR sample) is inlined in the `DATA` constant.
- `assets/`: the paper's figures as SVG, each with a light and a `_dark` version, plus the logo.
- `preview.png`: the social-card image (1200×630).

To preview locally, run `python3 -m http.server` in this directory and open http://localhost:8000.

Adapted from the page by Lizhang Chen at https://l-z-chen.github.io/relf/.
