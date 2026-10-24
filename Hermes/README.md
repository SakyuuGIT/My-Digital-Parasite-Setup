# Hermes — Digital Parasite

A [Hermes Agent](https://hermes-agent.nousresearch.com/docs) skin based on the Digital Parasite palette.

## Installation

1. Copy `digital-parasite.yaml` into your Hermes skins folder:
   - Default: `~/.hermes/skins/`
   - Custom `HERMES_HOME`: `$HERMES_HOME/skins/`
2. Activate the skin:
   - CLI: `/skin digital-parasite`
   - Or set `display.skin: digital-parasite` in `config.yaml`.

## Palette

| Token | Hex | Role |
| --- | --- | --- |
| Background | `#0a0a12` | Terminal background |
| Panel | `#12121f` | Status bar / menus |
| Rose | `#ff2d7a` | Primary accent (banner title, ui_accent) |
| Green | `#39ff88` | Secondary accent (banner_accent, ui_ok) |
| Cyan | `#00e5ff` | Shell dollar / info |
| Yellow | `#ffd93d` | Warnings |
| Text | `#e8e6f0` | Primary text |
| Muted | `#6b6880` | Dim / secondary text |
| Border | `#2a2a3f` | Borders / input rules |

## Notes

- The skin is single-mode (dark). Missing values inherit from the default Hermes skin.
- The `custom_css` block injects Digital Parasite colors into the Hermes Desktop GUI (chat background `#0a0a12`, sidebar `#12121f`).
- Includes a custom spinner with faces `(✨)`, `(🎀)`, `(⚡)` and thinking verbs (pulsing, infecting, glitching, parasiting, morphing, clinking).

Based on the Hermes skin system — see [CONTRIBUTING.md](https://github.com/NousResearch/hermes-agent/blob/main/CONTRIBUTING.md#adding-a-skin--theme).

---

Adapted and maintained by **Mattis Wattgen (Sakyuu)**. Original work by the respective authors credited above.
