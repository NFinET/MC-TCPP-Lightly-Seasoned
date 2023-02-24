# CHANGELOG VERSION INFO
| MC VERSION | PACK VERSION |
| :---: | :---: |
| 1.19.3 | v3.2.1 |

# SPECIAL NOTES
## Litematica has been added to the pack!
## !!! PLEASE READ THIS SECTION IF YOU WANT TO USE OR LEARN LITEMATICA !!!
### Litematica is a HIGHLY powerful building tool for saving, loading, and preview rendering designs to/from special schematic files. It's a highly complicated mod, and unless you think you need its features, you can safely ignore its existence entirely.
### It's important to note that Litematica's default "main" keybind was conflicting with another mod in the pack, and thus had to be changed. The main hot key for Litematica has been changed from "M" which conflicted with the World Map, to " . " (PERIOD). If any tutorial you find tells you to use a hotkey combo using the "M" key, instead use " . " in the same combo, and it will work as expected.
### [I highly recommend THIS tutorial for learning Litematica's basics](https://www.youtube.com/watch?v=pHa_GBLHulw)

# MODS ADDED
Mod Name | What the mod doin'?
--- | ---
Notes | Adds a configurable "Notes" menu with keybind, that allows you to keep notes within your game that can be per-world (save / server) or global, and pinned as a sidebar
Litematica | Adds an extremely in-depth and powerful schematic system, allowing you to save, load, and render schematic files to assist with building. This mod is VERY complex, and I HIGHLY recommend searching out tutorials on how to use it. However, do be aware that because of conflicting keybinds, the main hot key for Litematica has been changed from "M" which conflicted with the World Map, to " . " (PERIOD). If any tutorial you find tells you to use a hotkey combo using the "M" key, instead use " . " in the same combo, and it will work as expected.
MaLiLib | API Library, depencency of Litematica

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


