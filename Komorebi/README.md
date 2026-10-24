# Komorebi — Digital Parasite

[Komorebi](https://github.com/LGUG2Z/komorebi) is a tiling window manager for Windows. This folder contains the Komorebi configuration, bar configuration, and `whkd` keyboard shortcuts themed with the Digital Parasite palette.

## Files

| File | Description |
| --- | --- |
| `komorebi.json` | Main Komorebi config (workspaces, layouts, borders, animations) |
| `komorebi.bar.json` | Komorebi bar config (widgets, theme) |
| `whkdrc` | Keyboard shortcut configuration for `whkd` |

## Installation

1. Install [Komorebi](https://github.com/LGUG2Z/komorebi) and [whkd](https://github.com/LGUG2Z/whkd).
2. Copy `komorebi.json` to your user profile folder (`%USERPROFILE%\komorebi.json`).
3. Copy `komorebi.bar.json` to your user profile folder (`%USERPROFILE%\komorebi.bar.json`).
4. Copy `whkdrc` to `%USERPROFILE%\.config\whkdrc`.
5. Start Komorebi (`komorebic start`) and whkd (`whkd`).

## Palette

Border colors have been set to Digital Parasite:

| Token | Hex | Role |
| --- | --- | --- |
| Single (focused) | `#ff2d7a` | Rose — focused window border |
| Unfocused | `#6b6880` | Muted — unfocused window border |
| Floating | `#ff2d7a` | Rose — floating window border |
| Monocle | `#6b6880` | Muted — monocle window border |

## Notes

- The `komorebi.bar.json` uses the Base16 "Ashes" palette. You can customize the bar theme to match Digital Parasite by editing the `theme` section.
- Keyboard shortcuts use `alt` as the modifier key (vim-style navigation: h/j/k/l).
- Workspaces: monitor 1 has 3 BSP workspaces (I, II, III), monitor 2 has 3 Rows workspaces (Home, 2, 3).
- Ignored apps: Overwatch, Deadlock, WaveLink, PotPlayer, and others (floating/PiP).

---

Adapted and maintained by **Mattis Wattgen (Sakyuu)**. Original work by the respective authors credited above.