# Hermes — Digital Parasite

A [Hermes Agent](https://hermes-agent.nousresearch.com/docs) skin based on the Digital Parasite palette.

## Installation

1. Copy `digital-parasite.yaml` into your Hermes skins folder:
   - Default: `~/.hermes/skins/`
   - Custom `HERMES_HOME`: `$HERMES_HOME/skins/`
2. Activate the skin:
   - CLI: `/skin digital-parasite`
   - Or set `display.skin: digital-parasite` in `config.yaml`.

## Notes

- The skin is single-mode (dark). Missing values inherit from the default Hermes skin.
- The `custom_css` block injects Digital Parasite colors into the Hermes Desktop GUI (chat background and sidebar).
- Includes a custom spinner with faces `(✨)`, `(🎀)`, `(⚡)` and thinking verbs (pulsing, infecting, glitching, parasiting, morphing, clinking).

Based on the Hermes skin system — see [CONTRIBUTING.md](https://github.com/NousResearch/hermes-agent/blob/main/CONTRIBUTING.md#adding-a-skin--theme).

---

Adapted and maintained by **Mattis Wattgen (Sakyuu)**. Original work by the respective authors credited above.
