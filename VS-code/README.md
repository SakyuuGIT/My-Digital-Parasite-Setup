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

## Notes

The theme is angular, animated, and playful — errors pulse instead of staying static.

---

Adapted and maintained by **Mattis Wattgen (Sakyuu)**. Original work by the respective authors credited above.
