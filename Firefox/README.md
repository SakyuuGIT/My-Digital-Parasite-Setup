# Firefox — Digital Parasite Theme

A Firefox theme using the Digital Parasite palette. All UI elements use **square (no rounding) corners**.

Two layers:

- `userChrome.css` — deep UI styling (tabs, urlbar, menus, scrollbars, tooltips). This is the
  layer that actually restyles Firefox.
- `manifest.json` — WebExtension color theme (optional, temporary only).

## Install — the method that works on stock Firefox

Firefox Release refuses unsigned add-ons installed from a file. If you open the `.xpi`,
Firefox reports *"the add-on appears to be corrupt"* — that is a signature rule, not a broken
file. Use the CSS method instead (same one used for the Zen Browser theme):

1. Open `about:config` and set `toolkit.legacyUserProfileCustomizations.stylesheets` to `true`.
2. Open `about:support` → **Profile Folder** → **Open Folder**.
3. Create a `chrome` folder inside the profile.
4. Copy `userChrome.css` into that `chrome` folder.
5. Restart Firefox.

## Optional — temporary color theme

1. Open `about:debugging#/runtime/this-firefox`.
2. Click **Load Temporary Add-on…** and select `manifest.json`.
3. This lasts until Firefox is closed; it cannot be installed permanently without signing.

## Uninstallation

Remove `userChrome.css` from the profile's `chrome` folder and restart Firefox.

---

Adapted and maintained by **Sakyuu**. Based on the Digital Parasite color palette inspired by Capri (Cyberpunk: Edgerunners 2).
