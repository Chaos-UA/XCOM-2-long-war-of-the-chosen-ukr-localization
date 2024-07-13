Created by Iridar

More info here: https://www.patreon.com/Iridar

[WOTC] Missclick Protection

Most XCOM players had situations where they wanted to move a unit to a specific tile, but accidentlly clicked in the last moment onto a neighboring tile, leaving the soldier exposed. 

This mod aims to prevent that by forcing you to hover with your mouse above the target tile for 0.75 seconds before you can click for the unit to move there. The targeting cursor will be partially transparent while the delay is ticking.

I made this mod mostly for myself, so it's not as well polished as it could have been, but if it can save some soldiers' lives, it's probably worth sharing even in this state.

No idea whether it will work with a controller.

[h1]KNOWN ISSUES[/h1]

This mod does not affect melee abilities targeted by clicking a ground tile near the target. 

Sometimes the mod prevents you from moving to a specific tile even when the cursor indicates the delay is over. In this case simply move the mouse away from the tile and then back.

[h1]COMPATIBILITY[/h1]

This mod has two ModClassOverrides and will be incompatible with any other mods that also override these classes:
[code]XComTacticalController
XComPathingPawn[/code]

[url=https://steamcommunity.com/sharedfiles/filedetails/?id=1124288875][b][WotC] Gotcha Again[/b][/url] and [url=https://steamcommunity.com/sharedfiles/filedetails/?id=1136981000][b][WotC] Peek From Concealment UI Fix[/b][/url] also has an override to [b]XComPathingPawn[/b] and are [b][i]INCOMPATIBLE!!![/i][/b]. 

Unfortunate, but it is what it is. 

You can resolve the conflict with Gotcha Again by going to [b]..\steamapps\workshop\content\268500\1124288875\Config\XComEngine.ini[/b] and removing or commenting out this line:[code]
+ModClassOverrides=(BaseGameClass="XComPathingPawn", ModClass="XComPathingPawn_GA")[/code]

Technically this will disable a part of Gotcha Again's functionality, but I don't know which part, all I can say is that I haven't noticed anything while playing my own campaigns.

[h1]REQUIREMENTS[/h1]

Safe to add or remove mid-campaign. WOTC-only, no vanilla version planned.

[h1]CONFIGURATION[/h1]

This mod is configurable through this configuration file:
[code]..\steamapps\workshop\content\268500\2438647615\Config\XComUI.ini[/code]

[h1]ALTERNTIVES[/h1]

[b][url=https://steamcommunity.com/sharedfiles/filedetails/?id=1267323416]Misclick Confirm WOTC[/url][/b]

[h1]CREDITS AND DONATIONS[/h1]

Huge thanks to my wonderful patrons for their continued support. Please consider [b][url=https://www.patreon.com/Iridar]supporting me on Patreon[/url][/b] if you require tech support, have a suggestion for a feature, or simply wish to help me create more awesome mods.

