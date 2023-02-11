### Mod list is stored here in the code section since branch versioning can make versioned copies, allowing storing of legacy mod lists for obsolete versions.  
MC VERSION | PACK VERSION
:---: | :---:
1.19.3 | v3.01 

# FUNCTIONAL MODS
MOD | DESCRIPTION | DEPENDENCIES
--- | --- | ---
DeathLog | Keeps track of your deaths and takes snapshots of what you had on you when you died as well as the dimension and coordinates. Can be found in the Statistics screen when on a server | owo (owo-lib)
Extreme Sound Muffler | Adds a button to your inventory GUI that allows you to "muffle" (block) specific sound effects if you're tired of hearing them | 
Inventory Profiles Next | Adds inventory sorting buttons, the ability to "lock" inventory slots, allows using the scrollwheel to "push" and "pull" items to and from inventories, as well as auto-replacement of tools and items when they break / when a stack runs out in your hotbar; VERY configurable but VERY advanced | liblPN, Fabric Language Kotlin
Jade | Adds a tooltip to the center top of the screen that tells you information about what you're currently looking at | 
Light Overlay | Shows a configurable light-level overlay when toggled with F7 that allows you to see the light level per block, helping you figure out whether or not mobs can spawn there | Cloth Config API (Fabric), Architectury API (Fabric)
MixinTrace | Makes crashlogs better by providing .Mixin data (This helps identify if specific mods caused a crash) | 
Roughly Enough Items | Adds a search interface to inventory GUIs that takes up the left and right of the screen and allows you to search the recipes and uses of items by hitting a configurable hotkey while hovering your mouse over an item | Cloth Config API (Fabric), Architectury API (Fabric)
Stendhal | Adds special buttons to the chat input for unicode symbols, and also modifies the sign and book editing GUIs to have more features without breaking what they can normally do in Vanilla | 
Xaero's Minimap | Adds a configurable minimap with a waypoint system for navigation, integrates with Xaero's World Map | 
Xaero's World Map | Adds a saved map to places you explore accessible via the "M" key, integrates with Xaero's Minimap | 
Zoomify | Adds a configurable optical zoom that doesn't need a spyglass | Fabric Language Kotlin, YetAnotherConfigLib


# QUALITY OF LIFE MODS
MOD | DESCRIPTION | DEPENDENCIES
--- | --- | ---
AppleSkin | Adds some extra GUI & tooltip info about Health and Hunger / Saturation values to your GUI and to the tooltips of food items, to let you know how much food would restore | 
Beenfo | Adds extra tooltip info to Beehive items when they have been broken with silktouch and stored in an inventory; this info lets you see how much honey and how many bees are inside | 
Better Ping Display (Fabric) | Displays actual player ping in ms in the Tab menu instead of the connectivity bars | 
Chat Heads | Adds a little image of a player's head next to their name in chat messages to more easily tell players apart in chat | Cloth Config API (Fabric)
BetterF3 | Overhauls the Vanilla F3 debug menu with a configurable one that's a bit more human readable and is color coded | Cloth Config API (Fabric)
Clear Despawn (Fabric) | Makes it so that when dropped items are close to their despawn timer ending, they will begin to flash progressively faster until despawning | Cloth Config API (Fabric)
ClickThrough | Allows you to right-click containers and interactive things through signs and item frames, so you can label chests and stuff. Crouching and left or right clicking allows you to still access the sign / item frame as usual | 
Client Tweaks (Fabric Edition) | Adds a handful of QoL tweaks that can be configured, the list of tweaks can be found on the mod page on CurseForge or within the CurseForge launcher when selecting the mod, and the settings can be found within the mod's configuration menu in the Mod Menu | Balm (Fabric Edition)
Controlling | Adds a searchbar to the Controls menu for searching for keybindings by name of the binding or by the key used | 
DefaultSettings Fabric | Allows me to ship default configurations for the modpack and its updates without overwriting your personal ones every time | 
Enchantment Descriptions | Adds actual descriptions to the tooltips of enchantments that give brief explanations of what they actually do, configured in this pack to display when you're holding shift | Bookshelf
FuelInfo | Allows you to see how many more operations a Brewing Stand and Furnace can perform with their remaining fuel level by hovering your cursor over the fire icon | 
Giselbaer's Durability Viewer | Allows you to see the durability of any item that has taken damage in its tooltip, adds HUD for durability of your worn armor and held tool, adds HUD for how many arrows you have left when wielding a bow, shows the duration remaining of active effects, and adds an icon of a chest with a # of how many empty inventory slots you have remaining | 
Mod Menu | Adds a "Mods" button to the in-game menus to allow you to view what mods you have installed. This menu can give you some blurb info about each mod, and allow access to mod-specific config menus (if they have them) | 
Mouse Tweaks | Adds some extra controls to the mouse when interacting with inventories | 
No Night Vision Flickering | Replaces the default flickering / blinking when the Night Vision effect is wearing off with a gentle fade to avoid hurting your eyes | 
ToolTipFix | Fixes a longstanding GUI bug where Tooltips could get too long and extend off of the screen by allowing them to wrap the text upon hitting the edge | 


# OPTIMIZATION MODS
MOD | DESCRIPTION | DEPENDENCIES
--- | --- | ---
Better Beds | Fixes a vanilla oversight where beds use the wrong renderer, improves performance | 
Cull Less Leaves | Culls leaves beyond a default depth of 2 to improve performance when looking at leaves when not using Fast leaf rendering | YetAnotherConfigLib
Dynamic FPS | Reduces the game's volume caps its FPS when the game is unfocused, to save on CPU / GPU resources when the game is unfocused or minimized | 
Entity Culling (Fabric) | Allows the render engine to cull entities that are fully obstructed by offloading them to other CPU cores / threads, saving performance | 
FastAnim | Optimizes calculations for animating the limbs of entities to improve render performance | 
FerriteCore (Fabric) | Reduces Minecraft's RAM usage by optimizing some stuff  | 
LazyDFU | Check the modpage for exact explanation, but makes the game boot faster by not running code related to migrating worlds from old versions unless it's actually needed | 
Lithium (Fabric) | Tweaks and optimizes the code from a bunch of different game systems without actually changing any behaviors or functionality | 
Smooth Boot (Fabric) | Optimizes loading of worlds to be smoother and scale better on both high and low end systems | 
Starlight (Fabric) | Completely replaces the light engine to fix performance and lighting errors related to chunk generation and light updates |


# GRAPHICS MODS
MOD | DESCRIPTION | DEPENDENCIES
--- | --- | ---
Indium | Addon for Sodium to fix issues with mods that would normally be incompatible with it | Sodium
Iris Shaders | Shader mod that allows you apply Shader Packs, check the wiki on the github for a guide on finding and adding shader packs | Sodium
Reese's Sodium Options | Overhauls the default Sodium menu to be cleaner & nicer to use | Sodium
Sodium | Full replacement overhaul for Minecraft's rendering engine that greatly optimizes it, fixes issues from vanilla, and allows for more settings to be changed | 
Sodium Extras | Adds some bonus settings to Sodium in a new "Extras" tab in the Video Options menu from Sodium | Sodium


# BUGFIX MODS
MOD | DESCRIPTION | DEPENDENCIES
--- | --- | ---
Axolotl Bucket Fix | Fixes a vanilla issue, making it so Axolotl Buckets show the color of the contained Axolotl, and also whether they're a baby or adult | 
Debugify | Contains lots of bugfixes that can be optionally toggled off through the mod's configuration menu. Please note that not all bugfixes are strictly clientside, and if this is mod is on a server you connect to, some fixes will be "enforced" by the server as the actual code is fixed serverside | YetAnotherConfigLib
Memory Leak Fix | Plugs an obscure but known memory leak from Vanilla |
Nether Portal Fix | Fixes a bug from vanilla where Nether Portals can sometimes link up incorrectly when other portals are nearby, works in singleplayer, but the mod is required on the server to fix it in multiplayer | Balm (Fabric Edition)


# PURE APIS / DEPENDENCIES
MOD | REQUIRED BY: 
--- | ---
Architectury API (Fabric) | Light OVerlay, Roughly Enough Items
Balm (Fabric Edition) | Client Tweaks (Fabric Edition), Nether Portal Fix
Bookshelf | Enchantment Descriptions
Cloth Config API (Fabric) | Most Fabric mods that have their own config menu
Fabric API | Pretty much ALL Fabric mods
Fabric Language Kotlin | Inventory Profiles Next, Zoomify
liblPN | Inventory Profiles Next
owo (owo-lib) | DeathLog
YetAnotherConfigLib | Cull Less Leaves, Debugify, Zoomify

