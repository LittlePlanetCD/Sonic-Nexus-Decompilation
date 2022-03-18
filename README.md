
# Sonic Nexus (2008, RSDK) Decompilation for the Nintendo Switch
A Full Decompilation of Sonic Nexus (2008) by Taxman, made by RDC, ported to Nintendo Switch via hackery using HeyJoeWay's CD 1.1.2 switch port as a baseline for fixes.

# Installation Instructions

You can find downloads in releases.

   1. Make sure your Switch can run homebrew.
   2. Extract the contents of the zip to the root of your SD card.
   3. Copy the assets to /switch/nexus2008 on your Switch's SD card. You will need the following files/folders:
      
      Data Folder 
        
   (if you extracted the Data.bin for the folder, This lets you get Dev Menu support on startup and solve a bug regarding mods being loaded and crashing the game when using the Data.bin file only.)

   4. Start Sonic Nexus via hbmenu.

NOTE: It is recommended to give the game full RAM access. This means you shouldn't launch hbmenu from the album applet when running this. With the latest Atmosphere build and its default config, you can hold R while starting any game to open hbmenu with full RAM access. If you have any issues make sure the game has full RAM access before reporting them; launching as an applet will not be supported.

# Known Bugs

There is no way to press a button to access the dev menu when in game. (hopefully can be figured out eventually)
Mods crash the game when attempting to load them with a Data.bin rather than a "Data Folder". Unsure as to why this happens, because it happens on the original repository.

# Contact:
Join the [Retro Engine Modding Discord Server](https://dc.railgun.works/retroengine) for any extra questions you may need to know about the decompilation or modding it.
