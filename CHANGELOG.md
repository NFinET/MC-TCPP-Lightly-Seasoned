# CHANGELOG VERSION INFO
| MC VERSION | PACK VERSION |
| :---: | :---: |
| 1.19.3 | v3.2.1 |

# SPECIAL NOTES
## Litematica has been added to the pack!
## !!! PLEASE READ THIS SECTION IF YOU WANT TO USE OR LEARN LITEMATICA !!!
### Litematica is a HIGHLY powerful building tool for saving, loading, and preview rendering designs to/from special schematic files. It's a highly complicated mod, and unless you think you need its features, you can safely ignore its existence entirely.
### [Go HERE to the wiki page for Litematica in this modpack to read the keybind changes, a beginner tutorial, and other info!](https://github.com/NFinET/MC-TCPP-Lightly-Seasoned/wiki/Litematica-Important-Info)

# MODS ADDED
Mod Name | What the mod doin'?
--- | ---
Capes [Fabric/Forge] | Allows you to see and use capes from Optifine, LabyMod, and the MinecraftCapes mod; Only other people using this mod can see capes you add to yourself from it
LambDynamicLights | Allows you to see / use dynamic lights when holding items that create light. Important to note, this light is only rendered and not "real", and thus doesn't count for lighting-based calculation mechanics, like spawning of mobs
Litematica | Adds an extremely in-depth and powerful schematic system, allowing you to save, load, and render schematic files to assist with building. This mod is VERY complex, and some changes were made to its keybinds. If you want to use this mod AT ALL, please see the wiki page dedicated to it [>>HERE<<](https://github.com/NFinET/MC-TCPP-Lightly-Seasoned/wiki/Litematica-Important-Info)
MaLiLib | API Library, depencency of Litematica
Model Gap Fix | Fixes a vanilla issue with the model renderer that causes weird gaps / seams in some 3D models and in held items
Notes | Adds a configurable "Notes" menu with keybind, that allows you to keep notes within your game that can be per-world (save / server) or global, and pinned as a sidebar. For this modpack, the keybind is "J", as the mod's default had conflicts with other mods
Puzzle | Adds better GUI & configuration to graphics options

# MODS UPDATED
Mod Name | Prior Version | New Version
--- | --- | --- 
Architectury API | 7.0.66 | 7.1.70
Chat Heads | 0.9.0 | 0.10.4
Entity Culling Fabric | 1.5.2 | 1.6.1
Fabric API | 0.73.2 | 0.75.1
Fabric Language Kotlin | fabric-language-kotlin-1.9.0+kotlin.1.8.0 | fabric-language-kotlin-1.9.1+kotlin.1.8.10 
Indium | 1.0.12 | 1.0.14 
Iris Shaders | 1.5.1 | 1.5.2 
oWo (owo-lib) | 0.10.1 | 0.10.2
Roughly Enough Items | 10.0.586 | 10.0.592 
Sodium | 0.4.8+build.22 | 0.4.9+build.23 
Sodium Extras | 0.4.16+mc1.19.3-build.91 | 0.4.17+mc1.19.3-build.95 
Xaero's Minimap | 22.17.1 | 23.1.0 
Xaero's World Map  | 1.28.8 | 1.28.9 


# CONFIGURATION CHANGES
* Notes (the mod)
  * Changed Notes keybind from "N" (which conflicted with the pack's keybind for Build Guide) to "J", think of it as "[J]ournal".

* Litematica
  * Generic
    *  "easyPlaceVanillaReach" set to "true"; (Reduces easyPlace reach from 6 to vanilla 4.5 so servers won’t reject far block placement)
  * Hotkeys
    *  Changed a LOT of keybinds that all used "M" as their main key, since that is already in use by Xaero's World Map. The "main key" for Litematica is now " . " (PERIOD). All default Litematica keybinds that used "M" in them have been changed to use " ." (PERIOD), but are otherwise exactly the same. Details on the keybinds can be found in the table below. Keybinds are listed in the order they appear in Litematica's "HOTKEYS" menu tab.
  *  Additionally added 1 new binding for "executeOperation", bound to PERIOD + U; this action was by default not bound to anything.  

Litematica Keybind | New Bind
--- | --- 
addSelectionBox | PERIOD + A
executeOperation | PERIOD + U 
layerModeNext | PERIOD + PAGE_UP
layerModePrevious | PERIOD + PAGE_DOWN
openGuiMainMenu | PERIOD
openGuiMaterialList | PERIOD + L
openGuiSchematicPlacements | PERIOD + P
openGuiSchematicVerifier | PERIOD + V
openGuiSelectionManager | PERIOD + S
openGuiSettings | PERIOD + C
pickBlockToggle | PERIOD + BUTTON_3 (Middle mouse)
rerenderSchematic | F3 + PERIOD
selectionModeCycle | LEFT_CONTROL + PERIOD
toggleAllRendering | PERIOD + R
toggleSchematicRendering | PERIOD + G
toolEnabledToggle | PERIOD + T


