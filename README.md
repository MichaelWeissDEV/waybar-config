# Waybar configuration

Wayland-Panel mit Desktop-, Audio-, Netzwerk- und Systemanzeigen.

**[Vollständige Dokumentation](https://arch-dotfiles.readthedocs.io/en/latest/waybar/)** ·
[Komponenten](https://arch-dotfiles.readthedocs.io/en/latest/components/#waybar) ·
[Installation und Updates](https://arch-dotfiles.readthedocs.io/en/latest/arch-package/)

```bash
curl -fsSL https://raw.githubusercontent.com/MichaelWeissDEV/dotfiles/main/install.sh | bash -s -- waybar
```

Paket: `arch-dotfiles-waybar`. Dateien: `~/.config/waybar/config.jsonc`, `style.css`
und `power_menu.xml`. Module, Bedienung und Anpassungen sind im Handbuch beschrieben.
Quellen hier pflegen und auf `main` pushen; nach erfolgreichem Registry-Build mit
`sudo pacman -Syu` aktualisieren. [PACKAGING.md](PACKAGING.md).

[![Package safety](https://github.com/MichaelWeissDEV/waybar-config/actions/workflows/package.yml/badge.svg)](https://github.com/MichaelWeissDEV/waybar-config/actions/workflows/package.yml)

[MIT-Lizenz](LICENSE).
