# battletech-inventory

Personal BattleTech reference for casual ~6,000 BV, 3062-era play (tech ≤ 3062, no Dark Age / esoteric gear).
Three static pages, Catppuccin Macchiato theme, deployable as-is via GitHub Pages.

| Page | What it is |
|------|------------|
| `index.html` | 'Mech inventory — owned minis grouped by chassis and by product |
| `clan-variants.html` | Clan config / BV reference |
| `forces.html` | 6,000 BV force lists (3 Inner Sphere lances, 6 Clan Stars) |

## Battle Value provenance

Every BV is **MUL BV 2.0 at 4/5 (Regular)**, verified against the
Master Unit List (masterunitlist.info), cross-checked with Sarna. No recalled figures.

The Inner Sphere lances were re-verified and corrected — four were materially off:

| 'Mech | Was | Verified | Δ |
|-------|-----|----------|---|
| Centurion CN9-YLW | 1,350 | **957** | −393 |
| Banshee BNC-3S | 1,290 | **1,751** | +461 |
| Hatamoto-Chi HTM-27T | 1,800 | **1,607** | −193 |
| Caesar CES-3R | 1,750 | **1,578** | −172 |

All three IS lances remain ≤ 6,000 and are buildable from owned minis.
See `diffs/forces.html.diff` for the full previous-session → verified diff.

## Deploy

Settings → Pages → Deploy from branch → `main` / root. Pages are plain HTML, no build step.
