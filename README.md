# FontForge — Visual Font Inspector

Inspect and preview any Google Font in your browser. Waterfall sizes, character map, kerning pairs, specimen sheets.

**Live Demo:** [fontforge-inspect.surge.sh](https://fontforge-inspect.surge.sh/)

## Features

- **34 Google Fonts** — Including CJK fonts (Noto Sans SC, Ma Shan Zheng, etc.)
- **Live preview** — Custom text, adjustable size and weight
- **Waterfall** — 13 sizes from 12px to 96px
- **Character map** — Basic Latin + Latin Extended with Unicode code points
- **Kerning pairs** — 28 common pair combinations
- **Weight slider** — 100–900 variable weight support
- **Italic toggle** — Regular/italic switching
- **Font search** — Quick filter in dropdown
- **Specimen export** — Download as PNG with full waterfall
- **Paragraph specimen** — Multi-column text preview

## Tech

- Google Fonts CDN for font loading
- Canvas API for specimen PNG generation
- Dynamic stylesheet injection for on-demand font loading
- Single HTML file, no build step

## License

MIT
