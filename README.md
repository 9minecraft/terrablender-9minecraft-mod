# TerraBlender — Combine Custom Biomes Across Every Dimension

TerraBlender 9minecraft Mod helps custom biome mods work together in the same world. It shares world space between different mods and the base game across the Overworld, the Nether, and the End. New lands blend with existing mountains, rivers, and oceans without overwriting each other. It also manages custom ground blocks so every environment looks right. This library adds no items or mobs on its own, but works in the background when your favorite biome mods require it.

## What this build is

An unofficial rebuild of **Adubbz**'s original work, kept running on current Minecraft releases by 9Minecraft Studios. Not affiliated with the original author and not endorsed by them.

Most of the porting work sits in the mixin layer. Each Minecraft release moves or renames the methods this mod hooks into, so the hooks are re-pointed and re-tested against that version rather than rewritten. The behaviour underneath is upstream's and is deliberately left alone — that is the part that makes the mod feel right, and it is not ours to redesign.

## Source code

This build is released under **LGPLv3**. The complete corresponding source ships inside the downloadable file under `META-INF/sources/`, next to the original licence text.

## Versions

| Minecraft | Loader |
|---|---|
| 26.3 | Fabric, fabric, NeoForge, neoforge |
| 1.21.11 | Fabric, fabric, NeoForge, neoforge |

## Getting the built mod

Install steps, the dependency list, the screenshot gallery and what changed in each release are kept together on the download page:

[9minecraft.net/terrablender-9minecraft-mod](https://www.9minecraft.net/terrablender-9minecraft-mod/)

## Credits

Original work by **Adubbz**. Port and maintenance by 9Minecraft Studios. Licensed LGPLv3; the upstream licence text ships inside every build.
