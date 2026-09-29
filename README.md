# WorldSonus Demo

Public demonstration website for **WorldSonus: Bringing Sound to Worlds**.

- Website: https://noizai.github.io/WorldSonus-demo/
- Model weights: https://huggingface.co/FF2416/WorldSonus

This repository contains only the static demo page, presentation assets, and
precomputed Mel visualizations. Model and training source code are not included.
Videos are served from the existing public media storage.

## Publishing

GitHub Pages serves the repository root from the `main` branch. Updates pushed
to `main` are published automatically. `.nojekyll` keeps this a plain static site.

To preview locally, run `python3 -m http.server 8000` in this directory.
