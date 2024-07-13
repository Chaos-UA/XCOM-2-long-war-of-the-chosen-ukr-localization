RUSTY REDUX
- amalgamated peek from concealment
- exposed things to configs
- expanded functionality
- updated MCM suite

https://steamcommunity.com/sharedfiles/filedetails/?id=629910798 Original Vanilla Gotcha
https://steamcommunity.com/sharedfiles/filedetails/?id=866874504 Original Vanilla Gotcha Again!
https://steamcommunity.com/sharedfiles/filedetails/?id=1124288875 Original WOTC Gotcha Again!

https://steamcommunity.com/sharedfiles/filedetails/?id=1123555539 Peek From Concealment
https://steamcommunity.com/sharedfiles/filedetails/?id=1136981000 Peek From Concealment UI Fix

https://steamcommunity.com/sharedfiles/filedetails/?id=2480522533 MissClick Protection
https://steamcommunity.com/sharedfiles/filedetails/?id=1267323416 MisClick Confirm

https://steamcommunity.com/sharedfiles/filedetails/?id=1127539414 Revert Overwatch Rules Change
https://steamcommunity.com/sharedfiles/filedetails/?id=2797341225 Crouch Lower 

https://steamcommunity.com/sharedfiles/filedetails/?id=2129065433 WOTC_UnitSelectionOrder

Based on WOTC GA v 1.42
================================================================================================
UPDATES
================================================================================================
v1.1
- Added immune to damage for Delayed Bomb damage post
- Added Frost and delayed world effect checking

v1.2
- Added Rus translation by Aks
- Exposed more hardcoded stuff to configs
- Enabled built-in detection and adjustments for RevertOw Rules change
- Added ShadowStep negation for overwatch & suppression
- Integrated MissClick Protection 

v1.3
- russkie update

v1.4
- added config version correctly, reset MCM configs

v1.5
- initial attempt to fix broken flank previews
- added back gremlin squadsight indicators
- updated the alpha for the LW LoneWolf perk to scale with potency

v1.6
- Added a playerturn start event for xcom turn that forces a unit flag refresh

v1.7
- code clean up

v1.8
- bugfix for overwatch

v1.9
- MCM logging and overwatch/suppression improvements

v2.0
- added pistoloverwatch to overwatch checks

v2.1
- improved Waypoint system markers curtesy of Iridar
- added a controller check to disable MCP if controller is detected

================================================================================================
STEAM DESC      https://steamcommunity.com/sharedfiles/filedetails/?id=3002469584
================================================================================================
[h1]What is this?[/h1]
Simply put this is a merge of [url=https://steamcommunity.com/sharedfiles/filedetails/?id=1124288875] WOTC Gotcha Again [/url]
with [url=https://steamcommunity.com/sharedfiles/filedetails/?id=1123555539] Peek From Concealment [/url] and its [url=https://steamcommunity.com/sharedfiles/filedetails/?id=1136981000] UI Fix [/url] and [url=https://steamcommunity.com/sharedfiles/filedetails/?id=2480522533] MissClick Protection [/url].

Gone are the days of needing to manually configure the [i]XComEngine.ini[/i] of these mods to resolve conflicts, things just work.

Improves on the LoS indicators that are shown when previewing moves.
Makes concealment more reasonable.
Exploits the waypoint system to denote hazards and things of interest.
Has miss-click protection enabled by default.

I have sought permission to upload this updated mod merge but got [i]NO RESPONSES[/i] from any of the Gotcha/Peek original authors.
If one of them sees this and wishes for the mod to be removed, I will [b]UNLIST[/b].

MissClick Protection was included with permission from [b]Iridar[/b].

[h1]Features[/h1]
Has the best of the 3 parent mods, plus some more stuff;[olist]
[*]Reduced the number of icon packs to the original [b]dotvhs[/b] default. I have never seen the other sets used, so I removed them purely as a modsize saver!
[*]Indicators for units:[list]
[*] Red Reticle: Can shoot this unit
[*] Yellow Reticle: Can shoot this unit, it will be flanked
[*] Green Reticle: Friendly unit will be in LoS
[*] Red/Yellow Diamond : Same as above but because of squadsight
[*] White Wolf: Scaling alpha icon for LoneWolf bonus, the clearer the icon the stronger your bonus
[*] Blue Cog: Can be attacked by gremlin/bit at squadsight range 
[*] Orange Cog: Can be hacked outside of normal vision rules [/list]
[*]Indicators for objects:[list]
[*] Neutralise VIP: The arrow for the VIP will update in-line with the above unit icons
[*] Destroy Objectives: The arrow for the objective will update to show if it is shootable, including by squadsight.
[*] Hacking Objectives: The arrow for the objective will update when hacking is possible from the new position.
[*] Hacking Doors: An new indicator showing if a door is hackable remotely from the new position
[*] Hacking Towers: When an ADVENT tower is spotted, an arrow will show the possibility of hacking the tower.
[*] Tower Hacking Indicators can be turned permantly on/off [/list]
[*]Indicators along movement path:[list]
[*] Marks points along the path where you encounter a hazard. The final path tile has a 'summary' of all effects.
[*] Effects noted: Noise, Smoke, Fire, Acid, Poison, Frost, Curse, Delayed Explosions (PsiBomb), Hunters Mark, Killzone Mark. These are also now config expandable.
[*] Effect Markers do not pop-up for units immune to that effects damage type.
[*] Overwatch/Suppression indicators: When moving through LoS of a hostile overwatch, a marker will be made if the movement triggers it.
[*] Overwatch/Suppression indicators won't show up if a unit has ShadowStep.
[*] Pod Activation indicators: When a move will trigger a pod activation, the tile on which you are first spotted will be indicated by a marker.
[*] The overwatch and pod indicators only take currently visible units into account, they are exclusively based on info available to you through the UI in vanilla (otherwise it would be cheating!).
This means that pods not visible to you before initiating a move, but will activate because of it, will NOT be indicated. Units in overwatch outside your vision will also NOT be indicated.
Units on overwatch using squadsight will only be indicated if another hostile can see you and the triggering location is visible to you before initiating the move.
This can be changed in the MCM config![/list]
[*]Peek From Concealment Incorporated, on by default. MCM toggleable![list]
[*]Peeking from a Cover-step-out no longer breaks concealment.
[*]Approach High-Cover blind corners and Low-Cover rooftop/skylight edges and not break concealment.
[*]You can now correctly ambush from opening a door.
[*]There is a 2-tile grace period to activate overwatch, as long as the start and end of your movement path are also concealed! MCM Editable!
[*]Enemy detection ranges are buffed by 1 tile to compensate.
[*]This mod fixes the movement preview UI to account for the Peek's modified concealment rules. This means you should only see a warning post if you're actually going to break concealment. 
[*]The floor marker is unchanged. However, you can turn these all off if you wish.[/list]
[*]Miss Click Protection Incorporated, on by default. MCM toggleable![list]
[*]This means you must hover over a tile before being allowed to click it.
[*]Delay for hover and puck alpha can be set in MCM.[/list]
[*]Fixes an issue with ShieldHP Damage Preview that made it remain flashing even after moving the mouse away.
[*]Mod now uses [b]MrNiceUKs[/b] MCM suite package
[/olist]
[h1]Config[/h1]
All of the Peek From Concealment & MissClick Protection settings added to the MCM configs.
Alot of the features of this mod can be changed in the MCM menu.
Some features might be expanded in the actual configs. (world effect hazards, perk names etc)

[h1]Compatibility[/h1]
Does not work with any of the original mod versions mentioned above in the opening statement.

Has [b]Mod Class Overrides[/b] for the following files;[olist]
[*][b]UIUnitFlagManager[/b]: For the LoS indicators functionality
[*][b]XComGameState_IndicatorArrow[/b]: For objective indicator icon.
[*][b]UISpecialMissionHUD_Arrows[/b]: To overrule the hiding of objective indicator when using grapple.
[*][b]X2GrapplePuck[/b]: So indicators can be shown when selecting grapple locations.
[*][b]XComPathingPawn[/b] and [b]X2MeleePathingPawn[/b]: Doing pathing post indicators.
[*][b]XComTacticalController[/b]: Used for MissClick Protection.
[/olist]

The [b]UI Unit Flag Manager[/b] MCO was perfect to add a console command [b][i]should[/i][/b] fully refresh "stuck" Unit Flags.
Please try [i]RustyFix_UFE_GAR_ForceFlagRefresh[/i] if you get them missing or stuck on screen.

Should work with [url=https://steamcommunity.com/sharedfiles/filedetails/?id=1127539414] Revert Overwatch Rules Change [/url]
Does not work with [url=https://steamcommunity.com/sharedfiles/filedetails/?id=2797341225] Crouch Lower [/url] although it does borrow some concepts ...
Does not work with [url=https://steamcommunity.com/sharedfiles/filedetails/?id=1267323416] Miss Click Confirm [/url] but the 'better Iridar' version is integrated, sooo ... 
Does not work with [url=https://steamcommunity.com/sharedfiles/filedetails/?id=2129065433] WOTC Unit Selection Order [/url] due to MCO clash, investigating for incorporation ...

[h1]Known Issues[/h1]
Some MCM Features only work from Strategy, they will not update correctly mid-tactical [b]!![/b]

MissClick Protection (MCP) has some issues if enabled (from the base mod);
- Does not affect melee abilities targeted by clicking a ground tile near the target. 
- Sometimes the MCP prevents you from moving to a tile even once the delay is over. Move the mouse from the tile to refresh.
[strike]- MCP may not work correctly for controller users[/strike] MCP auto-turns-off if a controller is in use, (overridess MCM-on setting)

[h1]Credits[/h1]
Obviously credits to the Authors of the original mods, [b]Gotcha Again![/b] was worked on by alot of talented modders, too many to list!
Huge thanks to [b]Iridar[/b] for allowing me to incorporate MCP.
Some ideas borrowed from [url=https://steamcommunity.com/sharedfiles/filedetails/?id=2797341225] Crouch Lower[/url] by [b]DavidTriune[/b]

Many Thanks to [b]Aks[/b] for the Russian Translation

As always a shoutout to the XCOM2 and MEME modding discords!

~ Enjoy [b]!![/b] and please buy me a [url=https://www.buymeacoffee.com/RustyDios] Cuppa Tea [/url]
===============================================================================
