# Military Tactics Card Deck Demo

Static GitHub Pages demo for a 52-card military tactics deck.

The root demo is based on the original six-card 3D mockup from `tactics_card_3d_demo_bundle/index.html`, expanded to use the full 52-card manifest and external WebP assets.

## Contents

- `index.html` - interactive 3D browser demo using the full 52-card deck.
- `assets/webp/` - WebP card faces used by the demo.
- `assets/png/` - print/export PNG card faces kept with the repo.
- `assets/previews/` - contact sheet previews.
- `data/manifest.json` and `data/manifest.csv` - source metadata for all 52 cards.
- `demos/original-six-card-demo.html` - original imported six-card demo.
- `demos/assets/` - assets required by the original six-card demo.

## Local Preview

```sh
python3 -m http.server 8080
```

Then open `http://localhost:8080`.
