# Zen Browser — Digital Parasite Theme

A Zen Browser theme (Firefox-based) using the Digital Parasite palette. All UI elements are **square** (no rounded corners) for a sharp, angular cyberpunk look — inspired by system24's unrounding.

## Installation

### Method 1: userChrome.css (recommended)

1. Open Zen Browser and go to `about:config`.
2. Search for `toolkit.legacyUserProfileCustomizations.stylesheets` and set it to `true`.
3. Open your Zen profile folder:
   - Go to `about:support` → **Profile Folder** → **Open Folder**.
4. Create a `chrome` folder if it doesn't exist.
5. Copy `digital-parasite.css` into the `chrome` folder.
6. Create or edit `userChrome.css` in the same `chrome` folder and add:
   ```css
   @import "digital-parasite.css";
   ```
7. Restart Zen Browser.

### Method 2: Replace existing userChrome.css

If you already have a `userChrome.css` (e.g., from Rose Pine), back it up first, then replace its contents with:

```css
@import "digital-parasite.css";
```

## Features

- Dark cyberpunk background
- Rose and green neon accents
- Cyan links
- **All UI elements are square** (tabs, urlbar, buttons, menus, scrollbars, tooltips)
- Custom scrollbars, buttons, inputs, tooltips
- Styled sidebar and toolbar
- Tab selection indicator (rose bottom border)
- URL bar focus (rose border, no glow)

## Notes

- The theme uses `!important` on all properties to override Zen's defaults.
- Dark mode only.
- Works with Zen Browser's sidebar, workspaces, and compact mode.

---

Adapted and maintained by **Sakyuu**. Based on the Digital Parasite color palette inspired by Capri (Cyberpunk: Edgerunners 2).