![DMMoD Logo large](https://github.com/DarkMasterMan0/DMMod/assets/87884578/9c781fee-a103-4212-835b-54e764fa8f28)

# Manual Installation and Launch or D2RLaunch Installation
Download the files by clicking the green `Code` button near the top of this page and download the ZIP, or click the latest `Release` version on the right side and download the ZIP. Extract the files from the ZIP.

Drop the top-level DMMod folder into your D2R `mods` folder (the file path will be `Diablo II Resurrected > mods > DMMod > DMMod.mpq` if you did it correctly), if you don't have a `mods` folder then create it in your D2R installation folder (the file path will be `Diablo II Resurrected > mods`).

Create a new shortcut of `D2R.exe` from your D2R installation folder then add `-mod DMMod -txt` to the target line (it will look similar to `"E:\Games\Diablo II Resurrected\D2R.exe" -mod DMMod -txt` if you did it correctly). You can now use this shortcut to launch D2R with DMMod as the active mod. 

If you prefer the Battle.net launcher then you can click the `Options` gear next to the `Play` button, click `Game Settings`, enable `Additional command line arguments` and add `-mod DMMod -txt` to the prompt.

You can also use Bonesy's D2RLaunch mod manager to launch DMMod or other D2R mods, download it from here: https://www.d2rmodding.com/d2rlaunch After launching D2RLaunch you can download DMMod using the `Download New Mod` button on the right side, select DMMod in the dropdown tab that appears and install. After installation select DMMod in the `Mod Choice` dropdown tab and click the `Play Mod` button.

**BACKUP YOUR SAVES OFTEN:** Any time your computer has a hard shutdown (crash, power outage, pulled plug, etc.) it will cause the active RAM to get corrupted which includes your currently active character and the respective shared stash (softcore/hardcore). You'll find your save files in `C:\Users\username\Saved Games\Diablo II Resurrected\DMMod`, you can backup the whole folder or just the `.d2s` (character) and `.d2i` (shared stash) files. D2RLaunch has the option to automate backups, you'll find it under the `Options > QoL Options > Auto-Backup Characters` section.

**NOTE:** If you use any of the Expanded Storage options in D2RLaunch you'll need to reinstall it every time DMMod is updated, otherwise you'll lose any items that are outside of the vanilla storage area.

You can check out older versions of DMMod at [DMMod Archive](https://github.com/DarkMasterMan0/DMMod-Archive), use the installation instructions above with the DMMod folder of whichever version you'd like.

# What is DMMod?
DMMod is a mostly vanilla (~90-95% vanilla) mod that aims to address some of the imbalances in vanilla D2R in regards to items and skills with a combination of nerfs, buffs, and other changes while attempting to maintain the "original feel" of the game. Some very minor changes to drop rates (some low level uniques being able to drop earlier and a new unique charm as a guaranteed drop from quest Hell Baal).

Some examples of the changes include buffs/changes to lots of the weaker sets and uniques (whether that be by increasing existing stats or adding new stats), a few buffs/changes to underused runewords (like Holy Thunder, Venom, and Wind) and nerfs to overtuned runewords (like Stealth, Spirit, Insight, Grief, Enigma, Mosaic outright removed, etc.), buffs/changes to underused skills (like Poison Dagger, Iron Maiden, and Defiance) and a few nerfs to overtuned skills (like Blessed Hammer and Holy Shield), changes to magic/rare item affixes (adding a maximum item level cap to lower tier affixes to trim down the affix pool at higher ilvls), and monster stat changes to assist physical characters (decreasing block chance of Act Bosses and Ubers [but increasing their defense to compensate], decreasing the level of Ubers, etc.).

DMMod is **NOT** designed for classic/non-expansion mode and does **NOT** support legacy graphics outside of a very few early mod changes (legacy graphics still work, it's just any new content with new graphics won't have graphics in legacy mode and will instead be invisible). Both of these are niche and I don't want to dedicate the effort in balancing/maintaining them.

Feel free to make your own changes, that's why I include the .txt files. :) If you decide to distribute your own version of DMMod then you must release it with your modified source code as per the GPL 3.0 license.

# Credits
Thanks to:

* Blizzard Entertainment and Vicarious Visions (now Blizzard Albany) for creating D2/D2R and allowing/expanding modding capabilities (wish we had official TCP/IP tho T_T).

* Bonesy for the big help with guidance on specific edits, his video guides, and the massive amount of effort he's put into the D2R modding scene in general. Check out his stuff on [D2RModding.com](D2RModding.com) and check out the D2R-Modding Discord!

* Nefarius and others at the Phrozen Keep for their many indepth .txt file guides for original D2, the vast majority of which are still applicable to D2R. Check them out at [d2mods.info](d2mods.info) and check out the Phrozen Keep Discord as well!

* Vaska, Pavke, and Arsteel for item ideas and various discussions.

* id Software for creating the awesome Doom games and the badass logo that I re-used for DMMod.

# Changelog
See [Patch Notes](Patch%20Notes.md) for the 1.00 and subsequent patch notes. All changelogs are left as they originally were at time of release (so they become outdated as more patches release, see the up to date changelog to see the current state of DMMod). Use Ctrl + F to find any change for a specific skill/item/monster/etc., if there's no results then it hasn't changed.
