# omarchy-terere

Light theme for [Omarchy](https://omarchy.org) — Tererê palette.

Warm butter-paper background with amber, terracotta red, and forest green accents. Designed as a daytime counterpart to [omarchy-yerba-mate](https://github.com/nfvelten/omarchy-yerba-mate).

## Palette

| Role        | Color     |
|-------------|-----------|
| Background  | `#fbf1c7` |
| Foreground  | `#3c3836` |
| Accent      | `#b57614` |
| Keywords    | `#9d0006` |
| Functions   | `#076678` |
| Strings     | `#79740e` |
| Comments    | `#928374` |

## Installation

```bash
omarchy-theme-install github.com/nfvelten/omarchy-terere
```

Or manually:

```bash
git clone https://github.com/nfvelten/omarchy-terere \
  ~/.config/omarchy/themes/terere
```

Then apply with:

```bash
omarchy-theme-set terere
```

## Files

| File          | Purpose |
|---------------|---------|
| `colors.toml` | ANSI 16-color palette + terminal colors |
| `btop.theme`  | Btop+ system monitor theme |
| `waybar.css`  | Waybar status bar colors |
| `neovim.lua`  | Neovim colorscheme selector |
| `icons.theme` | Icon theme |
| `vscode.json` | VSCode theme reference |
| `light.mode`  | Flag file — marks this as a light theme |

## Companion themes

- Dark variant: [omarchy-yerba-mate](https://github.com/nfvelten/omarchy-yerba-mate)
- Neovim colorscheme: [yerba-mate.nvim](https://github.com/nfvelten/yerba-mate.nvim)
- Obsidian theme: [obsidian-yerba-mate](https://github.com/nfvelten/obsidian-yerba-mate)
