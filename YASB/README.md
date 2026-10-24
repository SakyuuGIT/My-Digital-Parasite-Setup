# YASB — Digital Parasite (Okinami)

A [YASB](https://github.com/amnweb/yasb) bar based on the [Okinami](https://github.com/MrDLingters/Okinami_YASB) theme by MrDLingters, recolored with the Digital Parasite palette.

## Installation

1. Install [YASB](https://github.com/amnweb/yasb) (v2.0.7 or newer).
2. Copy `config.yaml` and `styles.css` into your YASB config folder (`~/.config/yasb`).
3. Install the required fonts: **JetBrainsMono Nerd Font Propo** and **Segoe Fluent Icons**.
4. Restart YASB.

## Theme switching

To switch between color schemes, open `styles.css` and leave **one** set of variables uncommented in the `colors` section. The Digital Parasite palette is active by default.

## Palette

| Token | Hex | Role |
| --- | --- | --- |
| Background | `#0a0a12` | Bar background |
| Background 2 | `#12121f` | Panels / popups |
| Accent | `#ff2d7a` | Primary accent (rose) |
| Text | `#e8e6f0` | Primary text |
| Accent Text | `#0a0a12` | Text on accent |
| Hover | `#39ff88` | Hover state (green) |
| Muted BG | `#0d0d18` | Muted backgrounds |
| Border | `#2a2a3f` | Borders |
| Red Flash | `#ff2d7a` | Alerts / flash |
| Subtext | `#6b6880` | Secondary text |

## Notes

The bar uses the `adaptive` style (islands). Adjust `image_path` in `config.yaml` to point to your wallpaper folder.

## Variants

This repository also includes two additional YASB variants based on the Digital Parasite palette:

- **[YASB-Akira](../YASB-Akira)** — i3WM-inspired, square corners, no rounding, bar at the top with a rose bottom border. Recommended for a sharp, angular look.
- **[YASB-Shibumi](../YASB-Shibumi)** — Hyprland-inspired layout.

Based on Okinami by MrDLingters (Darren Lingters), credited in the main repository README.

---

Adapted and maintained by **Mattis Wattgen (Sakyuu)**. Original work by the respective authors credited above.
