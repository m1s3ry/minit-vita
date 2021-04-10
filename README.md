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
5. Launch VitaShell on your Vita and connect to PC via FTP or USB. (***NOTE:*** *If you connect through USB, you will need to enable Windows to show hidden files and folders*)
6. Copy the resulting `game.win` to `ux0:app/MINITVITA/games`
7. Copy all of the other game files (except options.ini and data.win) to `ux0:app/MINITVITA/games`
8. Launch the game on your Vita and enjoy

_(You can also download the VPK from VitaDB, EasyVPK or VHBB. Patch and instructions are included in `ux0:app/MINITVITA/games`)_

## Changelog
### v1.1
- Added compatibility with Epic Game Store and GoG versions
- Fixed buttons displaying Xbox graphics
- Camera no longer crashes the game (but it doesn't save pictures yet)

## Known Bugs
* Fullscreen, and brightness sliders don't do anything
* Palette swap shader has been disabled
* Some rooms have slow framerate. PSV Shell is highly recommended (oc ES4 to 166 or 222mhz)

## Credits
Credits for the original game go to Kitty Calis, Jan Willem Nijman, Jukio Kallio & Dominik Johann.
Additional credit for the port goes to @Grossleymoo for UTMT and helping/teaching me to port Vita games.

## Donations
If you want to support my work, you can [buy me a coffee here!](https://www.buymeacoffee.com/m1s3ry)

Also you can [follow me on twitter](https://www.twitter.com/m1s3ry_)
