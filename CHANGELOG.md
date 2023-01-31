# CHANGELOG VERSION INFO
| MC VERSION | PACK VERSION |
| :---: | :---: |
| 1.19.3 | v3.01 |

# MODS ADDED
### (These mods were all actually added in v3.0)
Mod Name | What the mod doin'?
--- | ---
Axolotl Bucket Fix | Fixes item icons for Axolotl Buckets to properly show their color and if they're an adult or a baby
Enchantment Descriptions | Adds descriptions of enchantments to tooltips of enchanted items (mod set so they show up only when holding Left Shift)
Bookshelf | API / Dependency required for Enchantment Descriptions
Light Overlay | Adds a toggle-able light level overlay visible by hitting F7, configurable
Better Beds | Fixes an ancient oversight from Vanilla Minecraft where beds use the Block Entity renderer instead of the Model Renderer, improves performance, also comes with optional resource packs to upgrade bed models
DeathLog | Keeps track of deaths and takes snapshots of your inventory, dimension, and coordinates on death, visible from a new "DeathLog" menu added to the top left of the Statistics menu
owo (owo-lib) | API / Dependency, required for DeathLog
Chat Heads | Adds a little image of a player's head next to their name in chat messages to more easily tell players apart in chat
Giselbaer's Durability Viewer | Allows you to see the durability of any item that has taken damage in its tooltip, adds HUD for durability of your worn armor and held tool, adds HUD for how many arrows you have left when wielding a bow, shows the duration remaining of active effects, and adds an icon of a chest with a # of how many empty inventory slots you have remaining
FuelInfo | Allows you to see how many more operations a Brewing Stand, Furnace, Blast Furnace, and Smoker can complete with their remaining level of fuel by hovering the cursor over the burn progress bar
DefaultSettings | Not for players. Tool for modpack developers to ship default settings like keybinds with a modpack without forcibly overwriting a player's personal settings when the modpack is updated
Debugify | Lots of bugfixes that can be optionally toggled off through the mod's configuration menu. Please note that not all bugfixes are strictly clientside, and if this is added to the server, some fixes will be "enforced" by the server as the actual code is fixed serverside
Client Tweaks | Adds a handful of QoL tweaks that can be configured, the list of tweaks can be found on the mod page on CurseForge or within the CurseForge launcher when selecting the mod, and the settings can be found within the mod's configuration menu in the Mod Menu 


# CONFIGURATION CHANGES
### Note: This is only changes between the initial v3.0 published release and the subsequent v3.01 release. Not all configuration customizations were being properly written down before v3.01 development cus I forgot, whoops :)

* Debugify
  * Opt out of updates set to TRUE: If any bugfixes get added to this mod later, they will be disable by default so they can be reviewed before putting them into action
  * Gameplay fixes in Multiplayer set to TRUE: Any gameplay related bugfixes that are clientside but can still work in a multiplayer setting will be activated

* Enchantment Descriptions
  * Enchantment Descriptions will now only show up when holding left shift while hovering the cursor over an enchanted item

* Giselbaer's Durability Viewer
  * Armor Around Hotbar set to TRUE: armor durability HUD will now show on left and right of your hotbar instead of in the bottom right corner
  * Effect Duration set to TRUE: the active effects icons in the top right of the HUD will now show how much time remains. This time is shown in shorthand when over 1 minute, and seconds when lower
  * Set Window Title to FALSE: this is completely pointless functionality that shouldn’t have even been included in this mod
  * Percent to Show Damage set to 100 (default 80): I have 0 idea why this setting even exists as it doesn’t make ANY fucking sense. By default, the numbers on the HUD show how much damage the item has taken instead of its actual remaining durability if the remaining durability is over this %? By setting this to 100, the item’s remaining durability is ALWAYS what’s displayed on the HUD instead
  * Show Free Inventory Slots set to TRUE: Adds a chest icon to the HUD with a number over it, this # is how many empty inventory slots you have remaining
  * Warning Mode set to NONE: Disables durability warnings from this mod, as the modpack already has them from Inventory Profiles Next

* Xaero's Minimap
  * Key Bind for "Quick Waypoint" changed from Numpad + to " = " (equals), Quick Waypoint functions similar to the Add Waypoint keybind " B ", but the waypoint it adds is specially marked as Temporary and will delete itself the next time you exit the world unless you change it to a permanent one in the Waypoints Menu (bound to " U ")
