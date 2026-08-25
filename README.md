# DedSec — Omarchy Theme

> Void black #050407 + lime #CBF705 — inspirado em dedsec3. Hacker, glitch, tech.

![preview](preview.png)

## Install

```bash
omarchy theme install https://github.com/rodriguesnich/omarchy-dedsec-theme.git
# ou menu: Super+Alt+Space > Install > Style > Theme > colar URL
```

## O que tematiza

- Terminal (Alacritty/Kitty/Ghostty/Foot via `colors.toml` gerado)
- btop, Chromium, Hyprland, Waybar, Mako, Walker
- Omarchy Shell `bar`, `menu`, `notifications`, `OSD`, `lock` (`shell.toml` #050407/#CBF705)
- Backgrounds, icons `Yaru-olive`, `keyboard.rgb` #CBF705
- Plymouth `unlock.png` (LUKS)

## Screensaver DedSec

`DEDSEC` box art em `backgrounds/02-screensaver-dedsec.txt` + hook `theme-set.d` (`dedsec*` → `DEDSEC` via `~/.config/omarchy/branding/screensaver.txt`). Efeitos `ttfx` tech: `decrypt`, `matrix`, `binarypath`, `laseretch` etc. sem `colorshift`.

Copie o hook opcional:

```bash
cp -r backgrounds/02-screensaver-dedsec.txt ~/.config/omarchy/branding/themes/dedsec.txt
# hook já vem se você usou dedsec3 antes
```

## Updates

```bash
omarchy theme update          # git pull todos .git
omarchy theme set dedsec
```

## Backgrounds

Cycle: `Super+Ctrl+Space` ou `omarchy theme bg next`

## Licença

MIT
