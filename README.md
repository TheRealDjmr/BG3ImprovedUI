
<p align="middle">
  <img src="https://i.imgur.com/6Zso95t.png"> 
</p>

29/10/24 - I've been struggling to write this but something is better than nothing. I'm not going to continue modding for the time being. Feel free to reach out if you want to work on ImpUI or any other UI mods. I just can't maintain mods on top of everything.

### Description
This mod is aimed at making changes to the overall user interface to improve usability as well as opening options to more potential mods.

### Patch 8 Restored
#### Patch 8 Restored Features
- Character Creation menus 
- Character Creation Level Up menus
- Character Creation Respec menus
- Character Creation icons for backgrounds

#### Recommendation after Patch 8
In general, all these steps can also be applied if a future patch or hotfix comes out; these are reflexes to have

- PC: Don't use multiple mod managers to manage your mods, choose one and stick with it
- PC: If you are using an external mod manager such as BG3MM, do not skip any updates to your mod manager or you risk having broken load orders and broken `modsettings.lsx` files
- PC: Vortex mod manager is not recommanded
- PC: Start fresh and delete `%AppData%\..\Local\Larian Studios\Baldur's Gate 3\PlayerProfiles\Public\modsettings.lsx`
- PC: Delete the contents from folder `%AppData%\..\Local\Larian Studios\Baldur's Gate 3\LevelCache`
- PC: Delete all your mods from folder `%AppData%\..\Local\Larian Studios\Baldur's Gate 3\Mods`
- PC: Delete all your mods from folder `%AppData%\..\Local\Larian Studios\Baldur's Gate 3\Local Mods`
- PC: Don't forget to enable & deploy your new mod list, it should create a new `modsettings.lsx`
- All Platforms: When a new update drop for Baldur's Gate 3, it's cleaner to re-download the game from scratch (because sometimes, when the game is updated, it keeps old update files from old version of the game and this makes the game unstable)
- All Platforms: It seems that ImpUI for Patch 8 works better for some people at the bottom of the load order, but it is not recommanded, ImpUI should be one of the first mod in your load order
- All Platforms: Do not use old saves from before patch 8, more specifically modded saves, start with a fresh new playthrough once you have reinstalled ImpUI and your mods for Patch 8
- All Platforms: Do not use UI mods that have not been updated for Patch 8 in addition to ImpUI
- All Platforms: Do not update your mods in the middle of a playthrough

### Patch 7 Features
#### Player Features
- Character Creation Layout tweaks: Redesigned Origin layout (the first screen you see when entering CC).
- Character Creation Layout tweaks: Adds full Facial Hair Colour selection.
- Character Respec tweaks: Adds Race and Background tabs, including racial passives that can be unselected then changed, and racial spells that can be switched.
- (Keyboard only) Character Creation Layout tweaks: Adds multiplayer tab that nests the multiplayer UI for Single Player, and allows the joining pop-up to appear for hosts when opened.
- (Keyboard only) CC/Level up Layout tweaks: Adds multiple scroll bars to Origins, Races, Subraces, Classes, Subclasses, Deity and Background selection for better support with modded options.
- (Controller only) Character Creation Layout tweaks: Hides appearance options when not relevant, adds "all colours" tickbox for highlights.
- (Controller only) Character Creation Layout tweaks: Adds slider values to options that have a numeric representation in the keyboard layout (Age, intensity).

#### Modder Features
- Character Creation Layout tweaks: Removes head scroll limit (Credit: Alana)
- CC/Level up Layout tweaks: Changes passive and equipment selection to turn into a scroll option when enough modded options are added - such as modded Eldritch Invocations. (Credit: Winterbrick)
- CC/Level up Layout tweaks: Adds passive and spell selection to Races (previously limited to Class only) (Credit: TrumanHarp)
- CC/Level up Layout tweaks: Changes Feat panel to have additional scroll options to support modded Feats with long descriptions and multiple options. (Credit: Lostsoul)
- Level up Layout tweaks: Adds Skill selection to both Races and Classes (previously limited to Classes with Expertise).

#### Custom Action Resource Icon Features
- Support for 4 different icon types - Keyboard icon, Keyboard CC/lvlup, Controller front icon, Controller resource icon. (BETA)
- Amended action resource functionality to make inserting custom action resources easier. QOL such as 10+ resources automatically convert to a number instead of resources.

### Patch 6 Features only!
#### Player Features
- Prevents annoying story error message box appearing when using mods
<p float="left" align="middle">
  <img src="https://i.imgur.com/dm5CsPu.png">
</p>

- Removes annoying reset tutorial/enable tutorials message box when entering CC
<p float="left" align="middle">
  <img src="https://i.imgur.com/piE3sv3.jpg">
</p>

- Hireling tweaks: Redesigned Hireling layout (makes better use of the dead space).

<b>OPTIONAL FILE REQUIRED</b>
- Replaces existing Minimap with smaller version (75% zoom, takes up less space on screen) or no Minimap (leaving the relevant buttons).
<p float="left" align="middle">
  <img src="https://i.imgur.com/cMii97G.jpg"><img src="https://i.imgur.com/hElvnJR.jpg">
</p>

#### Modder Features
- Character Creation Layout tweaks: Removes appearance tab restrictions allowing for modded slot use. (ex: Origin Hairstyles, Humans with tails) (Never utilised)
- Character Creation Layout tweaks: Changes Dragonborn Sorcerer Draconic Ancestry to allow for additional scale types. (Never utilised)
- Hireling tweaks: Adds multiple scroll bars to Hireling selection for better support with modded options.

#### <b>OPTIONAL FILE REQUIRED</b> Custom Asset Features
- Supports modded class/subclass icons, with a generic icon given to mods without a provided icon.
- Dynamic support for class/subclass icons that have not been provided, the image name would need to match the class/subclass name in classdescriptions.lsx. (Credit: LaughingLeader)
- Supports modded race/subrace icons, including custom names for Subraces such as Dragonborn.
- Supports modded action resource icons for Keyboard - Hotbar, Tooltips and CC/Levelup.
- Supports modded action resource icons for Controller - Tooltips, Action Radial "Cost:", Action Radial bottom resource bar and CC/Levelup.
- Dynamic support for action resource icons that have not been provided and fallback support when no entries are provided for CC/Levelup and Action Radial bottom resource bar.
- Better handling of action resources without icons, with placeholder stars added to each section and counted on Keyboard Hotbar. (Credit: juumeijin)
- Supports modded background icons (instead of a square block). (Credit: NellsRelo)
- Supports modded deity icons (instead of a square block). (Credit: Lostsoul)

### Discord
Feel free to join the [Larian Discord](https://discord.com/invite/larianstudios) server and discuss in the BG3 Modding Channels

### Attribution
- [Baldur's Gate 3](https://store.steampowered.com/app/1086940/Baldurs_Gate_3/), a game by [Larian Studios](http://larian.com/)
- Initial readme file generously donated by Zerd; check out their project here, [DnD Rebalancing](https://github.com/ZerdBG3/DnD-Rebalancing/)  

The latest mod updates will be available from GitHub first - https://github.com/TheRealDjmr/BG3ImprovedUI/releases
