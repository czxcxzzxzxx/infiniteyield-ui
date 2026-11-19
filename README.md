# Infinite Yield UI

A stripped-down, customizable UI framework for client-side Roblox Luau runtimes, extracted from [Infinite Yield](https://github.com/EdgeIY/infiniteyield). It keeps the menu, command bar, settings panels and executor compatibility layer, and removes the built-in commands so you can build your own on top.

> **Note:** This project is a derivative of Infinite Yield. See [Credits](#credits) and make sure you follow the original project's license terms before publishing.
---

## Installation

```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/nondevelopers/Infinite-Yield-UI/main/EgdeUI.luau"))()
```

## Customization

Search the source (Ctrl+F) for these tags to jump straight to the right spot:

| Tag | What it controls |
|---|---|
| `[CFG:NAME]` | Menu title, version string, credits text |
| `[CFG:LAYOUT]` | Menu size and starting position |
| `[CFG:ICONS]` | Asset folder and icon files |
| `[CFG:TOPBAR]` | Icon buttons in the menu header |
| `[CFG:SETTINGS]` | Buttons in the settings panel |
| `[CFG:DEFAULTS]` | Default prefix, scale, colors, saved settings |
| `[CFG:SAVEFILE]` | Name of the settings save file (`IY_FE.iy`) |
| `[CFG:DRAG]` | Drag behavior |
| `[CFG:ANIM]` | Slide speeds and hover delay |
| `[CFG:COMMANDS]` | Where to add commands and command-list entries |
| `[CFG:INTRO]` | Startup logo animation |

## Credits

- **Infinite Yield** by Edge, Zwolf, Moon, Toon, Peyton, ATP and contributors: original UI and code
- Modifications (UI/services extraction): *czxcxzzxzxx*
