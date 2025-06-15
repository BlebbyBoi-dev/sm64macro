# MACRO-SM64

**MACRO-SM64** is a high-scale experimental mod of Super Mario 64, focused on taking the classic game and pushing it to absurd physical and technical proportions. Imagine Mario stomping across a castle the size of a city, running on hardware hotter than the sun. That’s the kind of energy this project is going for.

This project is built on top of the [sm64 decompilation project](https://github.com/n64decomp/sm64), allowing full control over game assets, level design, object behavior, and engine tweaks.

## Project Goals

- Rebuild Peach's Castle Grounds to be massive — like, visible-from-space massive
- Scale up Mario, enemies, and objects to "macro" levels
- Modify level geometry, object placement, and physics to match the new scale
- Eventually output to a physically massive cartridge (conceptual, not just metaphorical)
- Optional: Create a counterpart **MICRO-SM64** mod as the smallest possible functional build

## Features

- Custom geometry and scripting for `castle_grounds`
- 10x scaled Mario with updated camera and collision logic
- Support for giant enemies, stretched level terrain, and larger-than-life set pieces
- Ability to build and test the game on real N64 hardware or emulators

## Folder Overview

| Folder | Contents |
|--------|----------|
| `/actors/` | Enemy, item, and NPC models/logic |
| `/levels/castle_grounds/` | Geometry, scripts, and assets for Castle Grounds |
| `/src/` | Game source code, including Mario’s movement and physics |
| `/sound/` | Music and SFX configuration |
| `/text/` | Course names, dialog strings, menu labels |
| `/tools/` | Scripts for asset conversion and build automation |

## Getting Started

1. **Clone the repo**:
   ```bash
   git clone https://github.com/yourusername/macro-sm64.git
   cd macro-sm64
