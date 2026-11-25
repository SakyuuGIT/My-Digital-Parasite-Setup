# Firefox — Digital Parasite Theme (square variant)

A Firefox theme using the Digital Parasite palette. All UI elements are **square** (no rounded corners), matching the Digital Parasite rule.

Two layers:

- `manifest.json` — WebExtension theme (browser chrome colors).
- `userChrome.css` — deep UI styling (tabs, urlbar, menus, scrollbars, tooltips).

## Installation

### 1. Color theme

1. Open `about:debugging#/runtime/this-firefox`.
2. Click **Load Temporary Add-on…**.
3. Select `manifest.json` in this folder.

### 2. Deep UI styling

1. Open `about:config`.
2. Set `toolkit.legacyUserProfileCustomizations.stylesheets` to `true`.
3. Open `about:support` → **Profile Folder** → **Open Folder**.
4. Create a `chrome` folder inside it.
5. Copy `userChrome.css` into that `chrome` folder.
6. Restart Firefox.

## Uninstallation

Remove `userChrome.css` from the `chrome` folder and disable the temporary add-on in
`about:debugging`.

---

Adapted and maintained by **Sakyuu**. Based on the Digital Parasite color palette inspired by Capri (Cyberpunk: Edgerunners 2).
