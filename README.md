# ES2-Achievement-Enabler
This mods enables ES2 achievements when using modding tools or mods.

This only makes two lines of changes from the base game, one to stop the game from disabling achievements when mods are loaded, and two to change the diagnostic message that appears when achievements are disabled because of mods.

You will not have any additional desyncs, and it is functional with every steam workshop mod. This is a very simple editing of game files.

To install this, hit Code > Download ZIP.
Extract the zip into C:\Program Files (x86)\Steam\steamapps\common\Endless Space 2\EndlessSpace2_Data\Managed

Say yes when it asks if it can replace files. If it doesn't ask you to replace any files, you have done it incorrectly.

Next, start your game and enable any gameplay mod.

To verify that this works, go to Documents/Endless Space 2/Temporary Files, and open the most recent temporary file (after launching a game and loading a mod that disables achievements). Hit Ctrl + F and look for this:

* `Cobbs has politely told your achievements to stay enabled.` If you see this, you correctly installed the mod. Good job.

Please note, not all types of mods disable achievements. Specifically, graphical and translation mods do not affect translations, and will not cause my message to show up, so keep that in mind.

To uninstall this, verify the game in your steam library. This will cause no damage to your save games whatsoever.

If you have any problems with getting this to work, feel free to join the [ESG Discord Server](https://discord.gg/eAfNtB3) and try asking for help.

If you can't find help there, and the Achievement Enabler still does not work, try Kuma's mod that does the same thing. You may find it [here](https://www.patreon.com/posts/46302678).
