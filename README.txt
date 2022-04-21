***********************************************************************************************
HARD CORPS FOR DHEWM 3 1.5.1 RELEASE CANDIDATE 1
***********************************************************************************************
Build: 0.8.65
Release Date: 10.15.2021

Hard Corps websites:
https://www.moddb.com/mods/hardcorps
https://Rivensin.com
https://revility.com

Hard Corps Source code:
https://github.com/dhewm/dhewm3-sdk

Dhewm3 website:
https://dhewm3.org/

***********************************************************************************************
ORIGINAL TEAM:
***********************************************************************************************

Revility:  		Artist & Team Lead
Ivan_the_B: 	Programmer
Neurological: 	Musician

***********************************************************************************************
2021 TEAM:
***********************************************************************************************

Revility:  		Jack of trades
Ivan_the_B: 	Programmer

***********************************************************************************************
2021 Dhewm 3 Source port:
***********************************************************************************************

Daniel Gibson

***********************************************************************************************
INTRODUCTION:
***********************************************************************************************

Hard Corps is the long awaited updated to the original Doom 3 mod "HardQore2", now running on the multi platform sourceport Dhewm 3 for Windows, Linux and Mac. Hard Corps brings fast paced, 2.5d side scrolling action to the Doom3 modern source port Dhewm3. Forget long winded plots, or boring puzzles, this is 110% non stop run n' gun slaughter. Strap on advanced UAC weaponry and take on the Forces of hell in this homage to classic action platformers such as Contra, Metal Slug, and Castlevania.

The modification contains two complete linked levels and 2 developer test map.

***********************************************************************************************
DESCRIPTION
***********************************************************************************************

Hard Corps is a modification for Dhewm 3.  It was originally a modification released for Doom 3 titled HardQore 2 in 2009.
The modification has been ported to Dhewm 3 along with many bug fixes, game play balances, improved gameplay, new features, improved visuals and new effects.
HC turns Doom3/Dhewm 3 into a 2.5d action side scroller.  It has been built with a load of features for a complete total conversion.

Dhewm3 is a source port of the original Doom3 (not Doom3 BFG, for that you may want to try RBDoom3BFG). It's known to work on Windows, Linux, macOS, FreeBSD, OpenBSD and AROS, but it should work (or be easily portable to) on any system that supports OpenGL 1.4 with ARB shaders, SDL and OpenAL.

Additionally we have included a Dev Documents folder in the demo.  These are various notes written
during the development of the mod.  They have not been proof read and have been left in to help anybody
wishing to create their own levels.

***********************************************************************************************
INSTALLING THE DHEWM 3 & HARD CORPS FOR WINDOWS.
***********************************************************************************************

Hard Corps comes bundled with the latest release of Dhewm 3.  Current bundles are available for windows 32-bit.
Please note the current version of dhewm3 included the archives is 1.5.1 Release Candidate 1.

Step 1: 
INSTALL THE CONTENTS OF THE ARCHIVE TO YOUR PC.
Drag & Drop or copy & paste the dhewm3 archive from the zip file to your pc.  Location does not matter.

Step 2:
COPY DOOM 3'S ASSETS TO DHEWM 3
In order to play the Dhewm3 source port, you will need to copy and paste the pak00*.pk4 files from your Doom3's base directory to your Dhewm3 base directory.  The same method is also needed if you wish to play the ROE expansion pack.  The Hard Corps mod will not run without the original Doom 3 assets inside the Dhewm3's base folder.  Your ready to play!

For a detailed guide on copying the files, Check the FAQ on the Dhewm3 github website:
https://github.com/dhewm/dhewm3/wiki/FAQ


***********************************************************************************************
LAUNCHING THE HARD CORPS MOD
***********************************************************************************************

The best way to launch Hard Corps is by double clicking on the included HardCorps.bat file.  It is highly recommended not to start the mod from Dhewm3's mod menu.  Launching Doom 3 mod's menu has been known to mess up up various settings... this includes the game not running in third-person by default.

***********************************************************************************************
CUSTOM DESKTOP SHORTCUT:
***********************************************************************************************
 
First you need to create a shortcut to the Dhewm3.exe short.  Rename it to Hard Corps.  
Next you need to right click on the shortcut and select properties.
Add the following line of text to the target path:
+set fs_game ruiner

Here is an example of what the new target path should look like:
C:\dhewm3\dhewm3.exe +set fs_game hardcorps

If your having any troubles with the mod, please feel to ask.


***********************************************************************************************
TROUBLESHOOTING:
***********************************************************************************************

Q: Will Hard Corps run on vanilla Doom 3?
A: No it will not.

Q: I see pure black or missing textures.
A: If your using an ATI card, some textures may appear black on the new content.  This is a DDS file issue.  I have heard,
but been able to confirm, that updating your ATI graphic card drivers will correct this issue.

Q: The screen is completely black when starting the game and starting the first level.
A: This is once again a known issue with ATI cards.  Disabling catalyst has been known to help out.  Most users have reported turning off HDR lighting and Bloom in the game's system's option resolved the issue.

Q: The game is in firstperson.
A: Most likely you started the mod through mod menu and not a bat file or shortcut.  To fix this you will will need to type the following the console.  To enable the console press the ` key.  Now type pm_thirdperson 1 and press enter.  You could also delete your Dhewm3/hardcorps configs and saves inside your my documents/mygames folder and restart the mod properly.

Q: The main menu, hud and other GUI related images are blurry.
A: Turn off image precompression in the game's system options.  Then go to the reload menu and select video restart.

Q: Sometimes the game crashes in certain locations without an error message.
A: This might happen if your using an ATI card.  Some ATI cards can not properly draw dds textures. Try removing or deleting the pak668_dds.pk4 inside your ruiner install.  Doing so will increase the visual quality. It will also lower performance.

Q: Where are my save and config files for the mod and Dhewm 3?
A: Inside you my documents/my games folder.  If you don't have this folder, it is created the first time you launch Dhewm 3 or any modification for it.

Q: Any gameplay tips?
A: The Charge attack deals a large amount of damage and also makes the player invulnerable.

Q: Are there tutorials to create my own levels? Will you add my custom map?
A:  Yes and Yes!  You can find many tutorials on the basics of making maps on our mod db page.  It it is highly advised to first learn the basics of mapping for Doom 3 as you will need it to get going.  The levels for the game were created with Dark Radiant.  DR is an open source and highly updated of the editor built into Doom3/Dhewm 3.  If you create a quality custom level, reach out to Revility.  He will gladly include any fun or high quality maps into the mod.


Any other problems or issues, please post at our moddb website: 
http://www.moddb.com/mods/hardcorps

***********************************************************************************************
KNOWN BUGS:
***********************************************************************************************

Jump Through Platforms:
It is possible to confuse the trigger logic of jump through platforms if the player is in just the right position.  This has been noted to happen during
a double jump.  The player will loose momentum and the jump will be cut short.

Enemy AI confusion:
AI has been noted to get a bit confused if the player is directly below or above them.  Enemies will constantly run around in circles above/below

Sound Beeps
Unlike vanilla Doom3, when a missing sound is called to play in Dhewm 3, a Beep sound is made.  They should have all been fixed.  If you encounter any, please report it so it can corrected.

Model and movable object clipping
While special moves are peformed by the player, it is possible for the character to briefly clip through the world.
Movable objects have been known to sometimes fall through the floor or other odd behavior.  This is the Doom 3's physics engine and not the mod.

***********************************************************************************************
RANDOM ADVICE BEFORE PLAYING:
***********************************************************************************************

-Conserving ammo:  The best way to conserve ammo is finish off your enemies with either the chainsaw or slide attack.

-Destruction:  Some objects in the levels can be destroyed using your weapons.

-Secrets:  There are secret paths and hidden doors in the levels.

-Interact key tips:  Icons will appear in the bottom left corner of the screen when the interact key can be used.

-3d pathways:  Some maps contain alternate path ways.  You can check this feature out in the dev test map. An arrow
icon will appear in the bottom left corner of the HUD at points which the player can change directions.  By pressing
the movement key direction of the arrow, the player will move that way.

-Exclamation Icon: A "!" symbol will appear on the bottom left corner of the HUD when you can use the interact key
or pick up weapons.

-The chainsaw is a great weapon to use against enemies who carry a shield.

-Jet pack notes:  After acquiring the jet pack, the player can fly for short periods of time.  
	Holding down the jump key while jumping will activate the jet pack.
	
-Double Jump notes:  After acquiring the double jump boots, the player can perform a second jump while they are
currently jumping.  This allows them to jump even higher.  The developer test map has this feature on by default.

***********************************************************************************************
2009/2021 CREDITS:
***********************************************************************************************

SPECIAL THANKS:
Pappy R
id Software
The Mod Database
Denton
Dinky
The Grave Sitter

List of the authors who's content & tools which are used in or to create Ruiner.

Denton: Denton mod sdk, HDR sdk and content usage
Bloodrayne: original gravity gun used during early builds
Acoustic Textures:  The source for many of Ruiner's textures
Andrew Hill: Serengrove props and texture
Kaiser: Doom 64 pc port sounds and music
Dinky: Icon of Sin model and Animations
Neurological: Musician
Revility: Hard Corps project Lead, original concept, modeler, artist, and much more.
Ivan_The_B:  Coding many of HC's features, tweaking the camera, and so much more.
Ivan_The_B:  Fragging Free content and features including bots
Ivan_the_B: Permission to release the source code under GPL.
rsjrv99: Malwrath & Fiend skins
Happy Friar: Original flame thrower code and FX
Rebb: ambient lighting fix shader mod
TheRealSceneGraphManager: Chromatic Dispersion Special FX (improved heat haze shader mod)
Alex Jeffrey: Water source shaders, textures and materials.
The Dark Mod Team: For creating and constantly updating the fantastic Dark Radiant. http://darkradiant.sourceforge.net
6th Venom: Main Menu mod and 2009 tester
Kiltron: 2009 tester
Kev
aulucifer: original 2d control code
Phil:	improvements to aulucifer's 2d control code.  This was the HQ2 control system.
Phil: Programmer for the original HardQore mod for Quake 4... which helped start this all back in 2005-2007

***********************************************************************************************
LEGAL STUFF:
***********************************************************************************************

- This archive may be freely distributed as far as the contents are not edited or removed.
- You cannot release modified unofficial versions of the whole mod.
- The source code for Hard Corps is GPL... not the assets!
- You may not include or distribute this mod in any sort of commercial product without permission from the authors.
- If you wish to use anything here in your projects, feel free to contact us through our mod db website:
	http://www.moddb.com/mods/hardcorps

***********************************************************************************************
***********************************************************************************************
"Scarlet Rivensin: The Ruiner name, story and the characters contained within it are a copyright and Trademark of Jim Kern. 1998-2018"
***********************************************************************************************
***********************************************************************************************

