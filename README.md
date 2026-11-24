# omarchy-blackbird-theme

SR-71 Stratosphere Cockpit theme for [Omarchy Linux](https://omarchy.org), calibrated directly to Blackbird's default Hero Flight Deck `synthwave` palette (`#0b0120` deep stratosphere sky, `#ff2fd0` rim magenta, `#05d9e8` Mach cyan, `#ff9a3c` afterburner amber).

## Install on Omarchy

```sh
omarchy-theme-install https://github.com/antimeme-ai/omarchy-blackbird-theme
```

Or via the `omarchy` CLI:

```sh
omarchy theme install https://github.com/antimeme-ai/omarchy-blackbird-theme
omarchy theme set blackbird
```

## Pairing with Blackbird Theme Sync

Place `50-blackbird` in `~/.config/omarchy/hooks/theme-set.d/50-blackbird` (`chmod +x`) so switching Omarchy themes (`Super + Ctrl + Shift + Space`) automatically updates `~/.config/blackbird/theme` across all 8 built-in Hero Flight Deck palettes.

## Wallpapers

Add high-resolution dark SR-71 cockpit wallpapers (`*.png` or `*.jpg`, 3840x2160 recommended) under [`backgrounds/`](backgrounds/README.md); Omarchy loads them automatically when the theme is active.

## License

[MIT](LICENSE) — Copyright (c) 2026 Antimeme AI LLC.
