# MY ricing Fork of Cyberpunk Theme (Hyprland)

> Man...after C those looks like gibbrish to me 

## ⌁ Keybinds ⛛

The theme modifier is **`$themeMod = SUPER + SHIFT`** (change it at the top of `theme.lua`). Open the full cheat-sheet with all keybinds anytime with **`SUPER+SHIFT+H`**.

### HUD & widgets

| Keybind | Action |
| --- | --- |
| `SUPER` / `SUPER + Space` | App launcher |
| `SUPER + SHIFT + Z` | Toggle HUD above / below windows |
| `SUPER + SHIFT + V` | Volume & Microphone modal |
| `SUPER + SHIFT + I` | Brightness modal |
| `SUPER + SHIFT + M` | Messages modal |
| `SUPER + SHIFT + O` | Music player |
| `SUPER + SHIFT + N` | Wi-Fi modal |
| `SUPER + SHIFT + G` | Netterminal: See Stocks, Crypto or News |
| `SUPER + SHIFT + X` | Dismiss Notifications |
| `SUPER + SHIFT + U` | System Upgrade modal |
| `SUPER + SHIFT + B` | Bluetooth modal |
| `SUPER + SHIFT + P` | Power menu |
| `SUPER + SHIFT + W` | 7-day weather forecast (double-click the city to change location) |
| `SUPER + SHIFT + -` | System time: timezone, NTP sync, manual set |
| `SUPER + SHIFT + Y` | Battery modal |
| `SUPER + SHIFT + C` | CPU / RAM / system modal |
| `SUPER + SHIFT + H` | Keybind help |

### System & capture

| Keybind | Action |
| --- | --- |
| `SUPER + SHIFT + T` | Netrunner terminal (cool-retro-term) |
| `SUPER + SHIFT + S` | Screenshot (region) |
| `SUPER + SHIFT + R` | Start / stop screen recording |
| `SUPER + SHIFT + K` | **Kill mode** (click a window to kill · `ESC` exits) |
| `SUPER + SHIFT + L` | Lock screen |
| `SUPER + D` | Peek desktop (hide windows) |

### Window management

| Keybind | Action |
| --- | --- |
| `SUPER + SHIFT + F` | Fullscreen toggle |
| `SUPER + F` | Float / tile toggle |
| `SUPER + ← → ↑ ↓` | Move focus |
| `SUPER + SHIFT + ← → ↑ ↓` | Move window |
| `CTRL + SHIFT + ← → ↑ ↓` | Resize window |
| `SUPER + 1…0` | Switch workspace (with the glitch transition) |
| `ALT + SHIFT + 1/2/3/4/5...` | Send window to workspace |
| 3-finger swipe (If using notebook)  ← / → | Previous / next workspace |

---

## ⌁ Layout

```
cyberpunk/
├─ core.ts              # HUD entry point (AGS / astal / GJS)
├─ theme.lua           # Hyprland full theme
├─ install.sh          
├─ components/
│  ├─ modules/         # The widgets and main components of the theme HD
│  ├─ login/           # Quickshell login
│  └─ style/           # cyber.scss and cyber.css
├─ scripts/            # launcher, screenshot, screenrecord, overkill, ws, terminal, and other used scripts.
├─ quickshell/         # Login screen using quickshell
├─ city.json           # Here is your saved location (starts by default in London,UK)
└─ assets/             # fonts, cursor, icons, kitty, kvantum, hyprbars, and resources
```

## ⌁ TO-DO

- [ ] Replace the Markets **News** tab's general and local news sources with
  computer-science research channels. Start with arXiv category feeds such as
  `cs.AI`, `cs.LG`, `cs.CL`, `cs.CV`, `cs.CR`, `cs.DC`, `cs.SE`, and `cs.HC`;
  preserve pagination, duplicate filtering, publication timestamps, summaries,
  source labels, error handling, and the existing modal interaction model.
- [ ] Add a small C program that emits structured, tagged status messages to
  the system journal so it can be followed with `journalctl -t <tag> -f`.
  Define a stable tag, command-line options for interval and sample count,
  graceful SIGINT/SIGTERM handling, and useful fields such as hostname, load,
  memory, uptime, and severity. Include a minimal Makefile and README build,
  run, and journal-query instructions.
- [ ] Fix the forecast minimap so it identifies the exact city selected in the
  weather search. Trace location persistence in `city.json` and the tile logic
  in `components/modules/sidepanel.ts`; remove any synthetic coordinate offset,
  correctly center/crop Web-Mercator tiles around the selected latitude and
  longitude, retain coordinate labels, and render a clear location marker.
- [ ] Add focused verification for the research-feed parser, journal monitor,
  and location-to-map conversion, including offline/error behavior and tile
  rendering for locations near longitude/date boundaries.




## Original Project Credits & Support Section (Untouched by me)


### ⌁ Credits

- Built on **[Hyprland](https://hypr.land)**, **[AGS / Aylur's GTK Shell](https://github.com/Aylur/ags)**, and **[astal](https://github.com/Aylur/astal)**.
- Lockscreen on **[quickshell](https://quickshell.org)**.
- Terminal: **[cool-retro-term](https://github.com/Swordfish90/cool-retro-term)**.
- The custom titlebars are a small cairo-bevel patch over Hyprland's **hyprbars** plugin, from original hyprbars by the Hyprland project.
- Projekt Red obviously for the game Cyberpunk 2077 UI Designs and aesthetics.
 
<div align="center">

### ❤️ Support

 #### if you enjoy the project and want to support future development:

[![Star on GitHub](https://img.shields.io/github/stars/ARCANGEL0/CyberArch-DotFiles?style=social)](https://github.com/ARCANGEL0/CyberArch-dotfiles)
[![Follow on GitHub](https://img.shields.io/github/followers/ARCANGEL0?style=social)](https://github.com/ARCANGEL0)
<br>

<a href='https://ko-fi.com/J3J7WTYV7' target='_blank'><img height='36' style='border:0px;height:36px;' src='https://storage.ko-fi.com/cdn/kofi3.png?v=6' border='0' alt='Buy Me a Coffee at ko-fi.com' /></a>
<br>
<strong>Hack the world. Byte by Byte.</strong> ⛛ <br>
𝝺𝗿𝗰𝗮𝗻𝗴𝗲𝗹𝗼 @ 2026


</div>
