# Font Wizard — Digital Parasite

[Font Wizard](https://github.com/karnyadavdev/FontWizard) changes the Windows 11 / 10 **system
font everywhere** — Start, taskbar, lock screen, File Explorer, and modern UWP / WinUI apps.

This setup uses **JetBrains Mono Nerd Font**.

## Installation

### 1. Install Font Wizard

```powershell
winget install -e --id karnyadavdev.FontWizard
```

### 2. Install JetBrains Mono Nerd Font

The font files are in `fonts/`. To install them:

1. Select all `.ttf` files in `fonts/`.
2. Right-click → **Install** (or **Install for all users**).
3. Restart any open applications.

> The font is the Nerd Font patched variant: it includes the glyphs and icons used by YASB,
> Windows Terminal, and the rest of this setup. Point apps to **JetBrainsMono Nerd Font**
> (not the plain JetBrains Mono).

### 3. Apply it as the system font

1. Open **Font Wizard**.
2. Pick **JetBrains Mono Nerd Font**.
3. Click **Apply** and sign out / restart when prompted.

## Font files

| File |
| --- |
| `JetBrainsMonoNerdFont-Bold.ttf` |
| `JetBrainsMonoNerdFont-BoldItalic.ttf` |
| `JetBrainsMonoNerdFont-ExtraBold.ttf` |
| `JetBrainsMonoNerdFont-ExtraBoldItalic.ttf` |
| `JetBrainsMonoNerdFont-ExtraLight.ttf` |
| `JetBrainsMonoNerdFont-ExtraLightItalic.ttf` |
| `JetBrainsMonoNerdFont-Italic.ttf` |
| `JetBrainsMonoNerdFont-Light.ttf` |
| `JetBrainsMonoNerdFont-LightItalic.ttf` |
| `JetBrainsMonoNerdFont-Medium.ttf` |
| `JetBrainsMonoNerdFont-MediumItalic.ttf` |
| `JetBrainsMonoNerdFont-Regular.ttf` |
| `JetBrainsMonoNerdFont-SemiBold.ttf` |
| `JetBrainsMonoNerdFont-SemiBoldItalic.ttf` |
| `JetBrainsMonoNerdFont-Thin.ttf` |
| `JetBrainsMonoNerdFont-ThinItalic.ttf` |

## Credits

- **Font Wizard:** [karnyadavdev/FontWizard](https://github.com/karnyadavdev/FontWizard)
- **JetBrains Mono:** [JetBrains](https://github.com/JetBrains/JetBrainsMono) — SIL Open Font License 1.1
- **Nerd Fonts patch:** [nerd-fonts](https://github.com/ryanoasis/nerd-fonts) — SIL Open Font License 1.1

---

Adapted and maintained by **Sakyuu**.
