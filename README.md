# rock-the-grok

Rock the Grok lead magnet landing (Hero's Arc).

Live: https://herosarc.github.io/rock-the-grok/

Static site, no build step. `main` is the source of truth; the `deploy-pages.yml` workflow force-pushes the site files (`index.html`, `chief-prompt.txt`, `assets/`, `.nojekyll`) to the `gh-pages` branch on every push to `main`. GitHub Pages serves the `gh-pages` branch (Settings > Pages > Deploy from a branch > `gh-pages`).
