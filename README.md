# assets-2d-castle

2D castle and medieval-themed game assets (walls, towers, characters, props)

## Stats

- **Total assets**: 613
- **License**: CC0-1.0 (all Kenney assets are public domain)
- **Source**: [kenney.nl](https://kenney.nl)

## Source Packs

| Pack | Assets | License | Link |
|------|--------|---------|------|
| Kenney Platformer Pack Medieval | 275 | CC0-1.0 | [Link](https://kenney.nl/assets/platformer-pack-medieval) |
| Kenney Tiny Battle | 202 | CC0-1.0 | [Link](https://kenney.nl/assets/tiny-battle) |
| Kenney Tiny Dungeon | 136 | CC0-1.0 | [Link](https://kenney.nl/assets/tiny-dungeon) |

## Structure

```
assets-2d-castle/
├── assets/kenney/    # Organized by source pack
├── previews/         # Pack preview images
├── LICENSES/         # License files per pack
├── manifest.json     # Machine-readable asset index (613 entries)
├── tags.json         # Genre, theme, style tags
└── README.md
```

## Usage

Browse `manifest.json` for the full asset index. Each entry includes:

```json
{
  "id": "kenney-<pack>/<asset-name>",
  "name": "Human Readable Name",
  "path": "assets/kenney/<pack>/...",
  "source": "Kenney <Pack Name>",
  "sourceUrl": "https://kenney.nl/assets/<pack>",
  "license": "CC0-1.0",
  "tags": [...],
  "fileType": "png|ogg|obj|..."
}
```

## License

All assets are **CC0-1.0** (Creative Commons Zero) — public domain, free for any use including commercial, no attribution required. See `LICENSES/` for original license files from each pack.
