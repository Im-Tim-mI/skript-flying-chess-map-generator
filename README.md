# Flying Chess Map Generator

**English** | [繁體中文](README.zh-TW.md)

Paints a 21 × 21-tile Chinese aeroplane chess (Flying Chess) board in colored concrete under your feet: four corner hangars, a two-tile-wide colored track, four home lanes and the central finish.

> This repository has two editions of the same script: **繁體中文 (zh-TW)** is the original used on the author's Traditional Chinese server, and **English** is a full translation (commands, messages and variable names) with the same features.

## Features

- Adjustable tile size 1-8 (default 2, which makes a 42 × 42-block board)
- Builds one row per tick to avoid lag spikes
- Only places blocks - no game mechanics

## Requirements

- [Paper](https://papermc.io/) server (developed on Paper 26.2 / Minecraft 26.2)
- [Skript](https://github.com/SkriptLang/Skript) (developed on 2.16.2)

## Installation

1. Install the plugins listed under [Requirements](#requirements).
2. Download **one** edition:

   | Edition | File(s) |
   |---|---|
   | English | [`en/flying-chess-map-generator.sk`](en/flying-chess-map-generator.sk) |
   | 繁體中文 (original) | [`zh-TW/飛行棋地圖產生器.sk`](zh-TW/%E9%A3%9B%E8%A1%8C%E6%A3%8B%E5%9C%B0%E5%9C%96%E7%94%A2%E7%94%9F%E5%99%A8.sk) |

3. Copy the `.sk` file(s) into `plugins/Skript/scripts/` on your server.
4. Run `/sk reload flying-chess-map-generator` (use the file name you copied) or restart the server.

> [!IMPORTANT]
> Install **only one** edition. Both editions are the same script in different languages - loading both makes them clash or run twice.

## Commands

| Command (English edition) | zh-TW edition | Description | Permission |
|---|---|---|---|
| `/flyingchess [size]` | `/flyingchess [每格大小]` | Build the board with you at the north-west corner, on the layer under your feet | everyone (players only) |

## Configuration

- Colors and layout are defined in the `fcBlock()` function.

## Notes

- The command has no permission - add one if regular players shouldn't be able to place up to ~28,000 blocks (tile size 8).

## Related projects

- [skript-monopoly-map-generator](https://github.com/Im-Tim-mI/skript-monopoly-map-generator) - Monopoly Map Generator

## License

**MIT + Commons Clause** - see [LICENSE](LICENSE) for the full text.

- ✅ You may use, copy, modify and share this script.
- ✅ You **may** install and run it - including modified versions - on Minecraft servers that charge money or are run for profit.
- ❌ You may **not** sell the script itself or modified versions of it, directly or indirectly, or require payment to obtain its files or source code.

Copyright (c) 2026 廷廷小教室、廷廷的家（Tim945）
