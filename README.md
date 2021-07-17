# Bastion: Hell and Hell (one hit kill) config mod
This config mod implements a "Hell and Hell" difficulty mode in Bastion, a 2011 game by Supergiant Games.

Based on the ["Hell and Hell" mode in the Devil May Cry series](https://devilmaycry.fandom.com/wiki/Difficulty_Mode), in this difficulty mode:
- You die in one hit
- Enemies retain their default HP

See also the [Heaven or Hell Bastion mod](https://github.com/rdimaio/bastion-heaven-or-hell-mod), where you die in one hit, but so do your enemies.

[Video showcase](https://www.youtube.com/watch?v=3YefWxCYlAU)

# Usage
## Applying the mod
There are two important file paths to identify:
- Your save game filepath, which should be one of these listed here: [Save game data location (from the PCGamingWiki)](https://www.pcgamingwiki.com/wiki/Bastion#Save_game_data_location)
- Your game config folder. Using Steam on Windows 10, this is `C:\Program Files (x86)\Steam\steamapps\common\Bastion\Content\Game`.

1. Back up your save files and copy them outside of your game folder. 
2. Back up the default game config folder (`C:\Program Files (x86)\Steam\steamapps\common\Bastion\Content\Game` on Windows) and copy it somewhere else; this will allow you to revert back to the default game functionality if you wish to do so.
3. Download this mod repository.
4. Copy the files in this repository to the game config folder.

## Removing the mod
Copy the files from the backed up default game config folder (the one you backed up in step 2 above) to the game's installation path config folder (`C:\Program Files (x86)\Steam\steamapps\common\Bastion\Content\Game` on Windows). In case you have lost the default config files, you can download them from [here](https://drive.google.com/drive/folders/1Utt0dDDyBNaicFL1XY62RYRI_FbCxuEn?usp=sharing).

# Notes
You can't die against the first enemy you encounter in the first level, because you have no health bar yet. You gain your health bar after that enemy, and you can now die in one hit.

After the first enemy, you will be dealt a scripted amount of damage. Because you only have 1 HP, this will kill you, but you can immediately revive.

The game will then think that you have to heal up at the fountain, which is not possible because you are at full health (1 HP). You can ignore the fountain and just kill the enemies around it, and then walk right into the saloon.

# Contributing
Feel free to propose changes and report any issues/bugs that you find! I have only tested this on Windows 10.