# icons-for-vscord

Modified icons for use in the **"Small Image URL"** section in VSCord's custom image settings.

> Fork of [VSCord](https://github.com/leonardssh/vscord) — forked to maintain a visible link to the original repository and give proper credit to the original assets.

## Why this fork?

VSCord's icons are designed to be used as **Large Image**, so they have significant internal padding. When placed in the **Small Image** slot, the actual icon becomes too small to see clearly.

This fork addresses that by cropping and/or scaling the icons so they look good at the smaller size.

## Structure
```
assets/
├── icon.png
└── icons/
    ├── agda.png     ← modified icons (reduced padding, icon fills more of the canvas)
    ├── ahk.png
    ├── android.png
    └── ...
```

## Variants

| Folder | Description |
|--------|-------------|
| `assets/icons/` | Original VSCord icons, modified to reduce padding |
| *(coming soon)* | Recolored or custom icons built from scratch |

## Usage

1. Host the image you want (e.g. via GitHub raw URL).
2. In VSCode, open your VSCord settings.
3. Paste the raw image URL in the **Small Image URL** field.

**Example raw URL format:**
```
https://raw.githubusercontent.com/raiksha/icons-for-vscord/refs/heads/main/assets/icons/idle.png
```

## Credits

All original icons belong to the [VSCord](https://github.com/leonardssh/vscord) project and its contributors. This fork only modifies sizing and padding for a specific use case.