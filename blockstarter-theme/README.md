# BlockStarter (WordPress Block Theme)

A minimal, professional **block theme starter** with sane defaults:
- Clean header template part
- Index template with query loop
- Modern palette, spacing, and typography via `theme.json`
- Full Site Editing compatible (WP 6.5+)

## Installation
1. Download the ZIP from Releases or this repository.
2. Upload to `wp-content/themes/` (folder name: `blockstarter-theme`).
3. Activate **BlockStarter** in **Appearance → Themes**.
4. Open **Appearance → Editor** (Site Editor) to customize.

## Structure
```
blockstarter-theme/
├─ style.css
├─ theme.json
├─ functions.php
├─ templates/
│  └─ index.html
└─ parts/
   └─ header.html
```

## Notes
- Uses a simple system font stack for performance.
- Palette includes `primary`, `dark`, `muted`, `light`.
- Layout sizes: content `720px`, wide `1140px`.

## License
GPL-2.0-or-later
