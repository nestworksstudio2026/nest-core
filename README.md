# NEST Core 0.1.1

Pack-specific integration for NEST on Minecraft 1.20.1 / Forge.
Internal ID: nest_resource_compat. Original code is MIT licensed; see LICENSE.

## Build

Requires Python 3, JDK 17 or newer, and ICU4J 71.1 from a legitimate Minecraft 1.20.1 installation. Third-party libraries are not bundled.
Set JAVAC to the javac executable if it is not on PATH. Set NEST_MC_LIBRARIES to the Minecraft installation libraries directory, containing com/ibm/icu/icu4j/71.1/icu4j-71.1.jar.
Run: python tools/build_resource_compat.py
Output: build/resource-compat/nest-core-0.1.1.jar
The published file is renamed nest-core-0.1.1.jar; its internal mod ID is unchanged.
Do not use --apply outside the NEST development workspace.

## Scope

Canonical acorn repair, language resource routing, targeted generated texture/chiseling fixes, and tutorial operation evidence. Requires Critters and Companions 2.7.1 and Paws & Claws. Other transformations target the versions pinned by NEST. This archive includes the transformer sources and Java helper sources, not original mod files, textures, translations, or Minecraft libraries.

## 0.1.1 resource fixes
Targeted runtime repairs for Better Archeology rotten-wood furniture palettes, Immersive Weathering single-color leaves and malformed Unusual Fish 1.1.10 expressions. No third-party assets are bundled. Quest evidence is unchanged.

## Source download
The complete source is in [NEST-Core-0.1.1-source.zip](NEST-Core-0.1.1-source.zip). Extract it before running the build command.
[CurseForge](https://www.curseforge.com/minecraft/mc-mods/nest-core) · [NEST community](https://discord.gg/Ecm4DUUzJ8)
