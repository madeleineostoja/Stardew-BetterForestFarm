# Better Forest Farm

An immersive, configurable alteration of the Forest (foraging) farm map for Stardew Valley. Compatible with all recolours.

## Features

- **Redesigned farm map** — a hand-crafted rework of the Forest farm layout with improved aesthetics and flow
- **Grassy Fields** *(optional)* — replaces most dirt with tillable grass and darkens existing non-tillable grass for a lusher, more forested feel
- **Secret Woods Shortcut** *(optional)* — adds a second entrance to the Secret Woods at the bottom of your farm, blocked by a hardwood log just like the main entrance

## Requirements

- [SMAPI](https://smapi.io/)
- [Content Patcher](https://www.nexusmods.com/stardewvalley/mods/1915) 2.0.0+

## Optional

- [Generic Mod Config Menu](https://www.nexusmods.com/stardewvalley/mods/5098) — configure options in-game from the main menu

## Installation

1. Install SMAPI and Content Patcher if you haven't already
2. Download `BetterForestFarm.zip` from the [releases page](../../releases)
3. Unzip into your `Stardew Valley/Mods` folder
4. Launch the game — select the **Forest** farm type when creating a new save

## Configuration

Options can be changed in `config.json` or via Generic Mod Config Menu:

| Option | Default | Description |
|---|---|---|
| `GrassyFields` | `false` | Replaces most dirt with tillable grass; darkens non-tillable grass |
| `WoodsShortcut` | `false` | Adds a shortcut warp to the Secret Woods from the bottom of the farm |

## Compatibility

- Works with all seasonal recolour mods — the map references vanilla tilesheet paths so any replacements apply automatically
- Forest farm type only; has no effect on other farm layouts
