# MHW Archipelago
A Monster Hunter World Randomizer Mod with implementation with [the Multi-Game Multi-World randomizer system Archipelago](https://archipelago.gg).

## What is Archipelago and how does it differ from other randomizers?
Basically Archipelago is a system that allows everyone to bring a game of their choice (as long as it is supported) and have them all blended together into one big fun cooperative multiplayer experience.

An example of this is as follows. Let's say I am playing Monster Hunter World and my friend is playing Hollow Knight. I end up completing one of my quests in World getting my friend his Mothwing Cloak. This allows him to go to new areas eventually getting me a weapon upgrade. This allows me to take on harder quests in order to get new items for the both of us. This continues until we both end up finishing our games.

## What the Mod Changes
This mod is still in very early alpha (as of September 2025) so many features I want to add haven't been implemented. This has a 4 year long project learning basically from scratch so this is only the beginning.

### IMPORTANT!!!
These changes are considered cheating! In order to provide other players a good experience only join and open up games to other Archipelago players. I know ICE has a dectection system for modded clients which I would like to implement at some point but is beyond my scope of current knowledge. Capcom is pretty antimodding so please show the community we are mostly a bunch of good apples.

* There are 3 win conditions (More May Be Added Later):
  *   Low Rank: Complete Invader In The Waste.
  *   High Rank: Complete Land of Convergence.
  *   Master Rank: Complete Paean of Guidance.
* Weapons and Armors have been overhauled to be progressive items to allow unique game progression.
* Endemic Life, most Quests, and Specialized Tools have been added as locations and/or items. More to come.
* Loot Boxes have been added as an interesting filler item.

## Contact and Bug Reporting
For questions, feedback, bug reports, or discussion related to the randomizer, please visit the "Monster Hunter World" thread in the [Archipelago Discord server](https://discord.com/invite/8Z65BR2).

## Installation
### Recommended Steps
Due to the mod messing with save files and being alpha I highly recommend backing up your save if you want to make sure your treasured save doesn't get lost. To find your game save it will be located C:\Program Files (x86)\Steam\userdata\<Your Steam ID>\582010\remote with the name of the file being SAVEDATA. Just copy itto a different location.

### Prerequisites
* Have Monster Hunter World installed ver 15.23.00.
  * Note: The mod has been designed with Iceborne in mind. It may not work correctly without it especially with incorrect settings. Following updates will address this.
* Install [Stracker's Loader](https://www.nexusmods.com/monsterhunterworld/mods/1982) and [Performace Booster and Plugin Extender](https://www.nexusmods.com/monsterhunterworld/mods/3473). Both are required for the mod to run properly.
* Install the latest Archipelago tools from [Archipelago's GitHub Release's Page](https://github.com/ArchipelagoMW/Archipelago/releases). Run the setup.
* Go to the releases page of this repo. If you are the one running Monster Hunter World you will need to download the .zip and yaml.

### Archipelago Setup
* Your yaml is your game settings. You can choose to change these settings with any text editor or keep it as default. When you have this configured in the way you want place it in the Archipelago\Players folder.
* If you have not already download the mhw.apworld. Place the mhw.apworld in the Archipelago\custom_worlds\ folder.
* Run ArchipelagoGenerate.exe.
* In Archipelago\output\ there should now be a file with a name like AP_44156741987196879179.zip.
* Open https://archipelago.gg/uploads, upload the zip file you just generated, and click "Create New Room" when the popup appears.

If you wish to have more players in your game just place the other yamls in the Players folder along with any other custom apworlds in the custom_worlds folder as needed.

### Modding Monster Hunter World
* If Stracker's Loader is installed properly there should be a folder in the game folder called nativePC.
* In the zip file will be an executable called ArchipelagoGenerator.exe in the folder called MHWGenerator.
* Once running the executable it will ask you to enter your Archipelago game info and the MHW game location.
  * You will need to do this every time you play a different slot for now.
* Launching the game will initiate a command prompt where you can enter commands in order to connect to Archipelago. You can also do this through the in game chat.

In order to reset the game to vanilla just remove all folders in nativePC beside plugins. If you remove the plugins folder it will uninstall the all the mods so you will need to install everything again.

## Credits
* Purpleranger, Parcosmic, and berrysoduh for being supportive throughout the years and keep pushing me through the hardships.
* ElusiveFluffy for allowing me to copy their homework on their existing MHW Randomizer.
* Fexty for answering my noob questions and pointing me in the right direction.
* AsteriskAmpersand and Moonbunnie for their hardwork and resources to the community that allowed me to learn.
* Thanks to Marechal-L for allowing me to use the Dark Souls III Archipelago mod as a foundation for this one.
* Thanks to black-silver for providing a code foundation for connecting to Archipelago.
