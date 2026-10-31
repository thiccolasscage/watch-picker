# watch-picker

Public GitHub Pages host for the SFW Watch Picker: https://thiccolasscage.github.io/watch-picker/

Mood packs, random spin, "Because you liked…", My list (CSV import from IMDb / Letterboxd) and Seen. Where-to-watch badges come from a Watchmode US snapshot. Everything runs in the browser, with no API keys and no network calls besides TMDB poster images. Your Seen list and My list stay in your browser's localStorage.

## This is a copy
The source lives in the private repo [thiccolasscage/its-popcorn-time](https://github.com/thiccolasscage/its-popcorn-time) under `docs/`. Edit it there, then copy these files over:

| here | from its-popcorn-time |
|---|---|
| `index.html` | `docs/index.html` |
| `catalog-with-where.json` | `docs/catalog-with-where.json` |
| `mood-packs.json` | `docs/mood-packs.json` |

Copied from its-popcorn-time @ `8308873`.

`.nojekyll` tells Pages to serve the files as-is.

## Pages
Settings → Pages → Deploy from a branch → `main` / `(root)`.

## Folder tree
```text
watch-picker/
├── index.html               # the picker (single file)
├── catalog-with-where.json  # 47 titles + Watchmode US availability
├── mood-packs.json          # 8 mood packs
├── .nojekyll
├── README.md
└── CLAUDE.md                # agent handoff
```
