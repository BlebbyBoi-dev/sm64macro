## MACRO-SM64

**MACRO-SM64** is a high-scale experimental mod of Super Mario 64, focused on taking the classic game and pushing it to absurd physical and technical proportions. Imagine Mario stomping across a castle the size of a city, running on hardware hotter than the sun. That’s the kind of energy this project is going for.

This project is built on top of the [sm64 decompilation project](https://github.com/n64decomp/sm64), allowing full control over game assets, level design, object behavior, and engine tweaks.

## Project Goals

# Level & World Design
Upscale Core Maps: Redesign levels at 10x scale, starting with castle_grounds, to emphasize massive traversal and scale-aware gameplay.

Macro Object Placement: Adjust enemy and object spawn positions for large-scale geometry.

Collision Overhaul: Update hitboxes, terrain flags, and camera zones for new proportions.

# Modeling & Asset Work
Custom Geometry: Replace original models with high-poly or oversized variants (including terrain, props, and characters).

Unique Visuals: Design new set pieces and structures to sell the “macro” concept — skyscraper trees, canyon-sized pipes, etc.

Retexturing: Create large-format textures with higher detail or exaggerated styles to suit the scale.

# Gameplay & Mechanics
Scaled Mario Physics: Tweak Mario's movement speed, jump height, and gravity to feel responsive on massive maps.

Camera Rework: Adjust the camera system to handle large-scale environments without constant clipping or poor framing.

Macro-Exclusive Hazards: Introduce new mechanics (giant rolling boulders, collapsing cliffs, etc.) designed for big environments.

# Engine & Build System
High-Scale Optimizations: Improve rendering or LOD handling to maintain performance on larger levels.

Physics Tweaks: Modify object physics to simulate weight and size (e.g., slower falling platforms, massive enemy knockback).

Custom Object Behavior: Write new object logic to support unique large-scale interactions (giant Koopa races, cannonball surfing, etc.).

# Hardware Integration (Experimental)
Custom Cartridge Concept: Build a real-world macro SM64 cartridge (oversized 3D print + functional internals).

Performance Tuning for Real Hardware: Ensure the mod runs (as best as possible) on actual N64 consoles with expanded memory, or EverDrive-style hardware.

# Parallel Project (MICRO-SM64)
Smallest Functional Build: Create a minimal build of SM64 that runs at 1/10th scale.

Extreme Downscaling Challenge: Compress geometry, remove unnecessary features, and experiment with ultra-minified level design.

Contrast Showcase: Create a side-by-side demo between macro and micro versions.

## Folder Overview

| Folder | Contents |
|--------|----------|
| `/actors/` | Enemy, item, and NPC models/logic |
| `/levels/castle_grounds/` | Geometry, scripts, and assets for Castle Grounds |
| `/src/` | Game source code, including Mario’s movement and physics |
| `/sound/` | Music and SFX configuration |
| `/text/` | Course names, dialog strings, menu labels |
| `/tools/` | Scripts for asset conversion and build automation |

