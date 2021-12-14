Welcome to.. Wizard Boys or something, I haven't actually named this project properly.

All of the source code located in this repository can be downloaded and built. 
All building, programming, and testing has been done in Visual Studio Enterprise 2019, for reference.
The software renderer may fail to build, for this project the graphics renderer was used,
if you need to use the software renderer for whatever reason you'll have to look online, or 
fix the errors yourself. The simplest way to play this mod is to create a new folder inside 
the `/Quake 2` folder, and name it whatever you'd like. Upon sucessfully building the game project
move the newly created gamex86.dll into the new mod folder. Lastly create a shortcut for the quake2.exe
and edit the shortcut target to add ` +set game ModFolderTime +map "q2dm1" ` at the end. Launching this
shortcut should now bring you directly into the mod.

The game:
Some of the gameplay has been modified for a final presentation, and therefore is extremely unbalanced
in order to demonstrate the mod.

The room you spawn in is essentially the "hub world". Behind your spawn will be three large health packs, which when collected
will select your class. From left to right these are fire mage, ice mage, and gravity mage. Three items will spawn to your right,
these in order from left to right are blood veil, quick charge, and free spell chance.
After selecting a class you can enter any of the 3 green portals to load into a dungeon.
Lastly, the classes and spells (guns) are as follows:

Gravity Mage:
  Grenade Launcher - Spell 1
  Hyperblaster - Spell 2
  BFG10k - Ultimate Spell
  
Fire Mage:
  Shotgun - Spell 1
  Railgun - Spell 2
  Rocket Launcher - Ultimate Spell
 
Ice Mage
  Blaster - Spell 1
  Super Shotgun - Spell 2
  Machinegun - Ultimate Spell
  
Enjoy!

--------------------------------------------------------------------------

This is the complete source code for Quake 2, version 3.19, buildable with
visual C++ 6.0.  The linux version should be buildable, but we haven't
tested it for the release.

The code is all licensed under the terms of the GPL (gnu public license).  
You should read the entire license, but the gist of it is that you can do 
anything you want with the code, including sell your new version.  The catch 
is that if you distribute new binary versions, you are required to make the 
entire source code available for free to everyone.

The primary intent of this release is for entertainment and educational 
purposes, but the GPL does allow commercial exploitation if you obey the 
full license.  If you want to do something commercial and you just can't bear 
to have your source changes released, we could still negotiate a separate 
license agreement (for $$$), but I would encourage you to just live with the 
GPL.

All of the Q2 data files remain copyrighted and licensed under the 
original terms, so you cannot redistribute data from the original game, but if 
you do a true total conversion, you can create a standalone game based on 
this code.

Thanks to Robert Duffy for doing the grunt work of building this release.

John Carmack
Id Software


