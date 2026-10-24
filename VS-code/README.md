# Visual Studio Code — Digital Parasite

Instructions for using the Digital Parasite color theme in Visual Studio Code.

## Installation (manual)

This repository provides a `settings.json` with the Digital Parasite color customizations. To apply them:

1. Open VS Code.
2. Open the Command Palette (`Ctrl + Shift + P`) and select **Preferences: Open User Settings (JSON)**.
3. Merge the contents of `settings.json` from this folder into your `settings.json`.
4. Reload VS Code if needed.

## Manual setup

Alternatively, add the following to your `settings.json`:

```json
{
  "workbench.colorTheme": "Digital Parasite",
  "editor.fontFamily": "JetBrains Mono, Consolas, monospace",
  "editor.fontSize": 13
}
```

## Palette

| Token | Hex | Role |
| --- | --- | --- |
| Background | `#0a0a12` | Editor background |
| Panel | `#12121f` | Sidebar / panels |
| Rose | `#ff2d7a` | Keywords / errors |
| Green | `#39ff88` | Strings / success |
| Cyan | `#00e5ff` | Functions / info |
| Yellow | `#ffd93d` | Numbers / warnings |
| Text | `#e8e6f0` | Primary text |
| Muted | `#6b6880` | Comments |

## Notes

The theme is angular, animated, and playful — errors pulse instead of staying static.
