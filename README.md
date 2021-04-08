# minit-vita
A patch to make Minit playable on Vita

###

## Disclaimer
This patch does not contain any game files from Minit. **You need the game files from your legally owned copy**.
If you don't have a copy of the game, you can buy it [HERE](https://store.steampowered.com/app/609490/Minit/)

## Instructions 
1. Download the VPK and install it on your hacked PS Vita
2. Download the patch and extract it anywhere. Open your newly created patch folder
3. If you have the Steam version of Minit, right click on it -> Manage -> Browse local files. Otherwise, find the folder in which Minit is installed
4. Copy `data.win` to your patch folder, and execute `apply_patch.bat`
5. Copy the resulting `game.win` to `ux0:app/MINITVITA/games`
6. Copy all of the other game files (except options.ini and data.win) to `ux0:app/MINITVITA/games`
7. Launch the game on your Vita and enjoy

_(You can also download the VPK from VitaDB, EasyVPK or VHBB. Patch and instructions are included in `ux0:app/MINITVITA/games`)_

## Known Bugs
* Fullscreen, and brightness sliders don't do anything
* The camera slows the framerate and doesn't save images. Use screenshots instead.
* Palette swap shader has been disabled
* At one point in the game, the stats room will have slow framerate

## Credits
Credits for the original game go to Kitty Calis, Jan Willem Nijman, Jukio Kallio & Dominik Johann.
Additional credit for the port goes to @Grossleymoo for UTMT and helping/teaching me to port Vita games.
