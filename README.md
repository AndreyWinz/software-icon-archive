# software-icon-archive

A community-maintained archive of software icons, sourced by extracting them directly from executables or locating official versions online.

[![License](https://img.shields.io/badge/license-CC0--1.0-blue.svg)](LICENSE)
[![Status](https://img.shields.io/badge/status-active%20development-green.svg)]()

## Purpose

Finding clean, high-quality icons for a specific piece of software can be surprisingly tedious. This repo serves as a single place to grab them — no hunting through installer files or blurry screenshots.

## Structure

Icons are organised by software name under the `/icons/` directory:

```
icons/
├── 7zip/
│   ├── 7zip_64x64.ico
│   └── 7zip_32x32.png
├── eclipse/
│   ├── eclipse_48x48.ico
│   └── eclipse_256x256.png
└── ...
```

Each software folder may contain icons in multiple formats and resolutions where available.

## Contributing

Suggestions for additions or corrections are welcome via issues, but this is a **curated archive** — all submissions are reviewed, and not everything will be accepted.

When suggesting a software title, include:

- The software name and version (if icon is version-specific)
- Where the icon came from (extracted from `.exe`/`.dll`, official website, press kit, etc.)
- The file(s) you'd like added

All icons are verified and processed before being committed to keep the archive consistent.

### Sourcing guidelines

- **Extracted from executable** — use a tool like [CONVERTICO](https://convertico.com/exe-icon-extractor/) to pull icons from `.exe` or `.dll` files
- **Official source** — link to the original download, press kit, or asset page
- Avoid upscaled or fan-made icons; the archive prioritises official originals

## Format & naming conventions

| File | Meaning |
|------|---------|
| `softwarename_256x256.ico` | 256×256 PNG export |
| `softwarename_512x512.ico` | 512×512 PNG export (when available) |

Stick to lowercase, no spaces — use underscores if needed.

## License

This archive is released under the [CC0 1.0 Universal Public Domain Dedication](LICENSE). To the extent possible under law, all original curation work in this repository has been waived of copyright. You can copy, modify, and distribute the contents without asking permission.

Note that the icons themselves are the intellectual property of their respective software vendors — CC0 applies to the archive's own work (structure, metadata, curation), not to the icons as third-party assets. If you are a rights holder and want an icon removed, please open an issue.

## Related tools

- [CONVERTICO](https://convertico.com/exe-icon-extractor/) — extract resources from Windows executables
- [IcoFX](https://icofx.ro/) — icon editor and converter

## Buy me a Coffee
If you think I deserve a little gift to support me and my creations, feel free to buy me a coffee!

Please include your GitHub username in the "Note" section so I can add you to the contributor list on my profile!

[![BuyMeACoffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-ffdd00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black)](https://revolut.me/andreygdl9)
