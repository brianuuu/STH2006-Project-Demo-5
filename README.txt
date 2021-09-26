---------------------------------------------------------------------------
------------------------STH2006 Project Demo 5-----------------------------
---------------------------------------------------------------------------
This is an unofficial project which imports all of Sonic The Hedgehog (2006) main stages from Xbox360/PS3 version into Sonic Generations on PC. This project aims to port the stages as similar to the original game as possible, but also includes changes which accommodate to the complete different physics and controls in Sonic Generations.

In this demo, you will be able to play 4 stages, Wave Ocean, Crisis City, Tropical Jungle and Kingdom Valley. You can find the warp gates to the stages inside Soleanna HUB world. If you are lost, the noticeboards scattered around the HUB will guide you where the warp gates are!

You are highly recommended to play with "Sonic 06 Definitive Experience" mod (download link below), you will be able to not only play with character models from 06, but also change the gameplay into 06 style, and also use recreated movesets from 06! Oh? There are iron boxes in New City HUB World, maybe if you use Sweep Kick on them......? (Note: only 2 specific of them works)

All the levels in this mod are designed to be able to play with both Generations physics and 06 physics from "Sonic 06 Definitive Experiece" mod, challenge yourself to get S-ranks with 06 physics, and find the 5 hidden Silver Medals within the stages!

This mod also supports both English and Japanese! Simply change the voice-over setting in option menu to your preferred language and you can listen to the respective dialog! However if you want to change the subtitle language you will have to change via Steam or regedit, read "Switching UI Language" section below.

You MUST play this mod with "Direct3D 9 Ex" enabled, download it at https://gamebanana.com/mods/50770

Finally, enabling "Better FxPipeline" is also highly recommended to enhance the overall experience!

Enjoy the demo!

------------------------------------------------------------
Requirements & Recommendations: 
------------------------------------------------------------
-Only works with HedgeModManager, SonicGMI is NOT supported!!!
-You MUST play this mod with "Direct3D 9 Ex" enabled, download it at https://gamebanana.com/mods/50770
-"Save file redirection" MUST be enabled, otherwise your original save will be overwritten
-Playing with "Sonic 06 Definitive Experience" mod is highly recommended, it must be high priority than this mod
-Enabling "Better FxPipeline" mod is also highly recommended, download it at https://gamebanana.com/mods/50765

------------------------------------------------------------
Technical Highlights:
------------------------------------------------------------
With the help of code injection, this mod can now achieve advance gameplay that cannot be done before, here are a few highlights:

-Enemy Triggers
This allows objects to be triggered by defeating enemies, this feature existed in Sonic Unleashed but has been removed in Sonic Generations, it has now been brought back. This also made defeating enemy leader destroying other enemies possible!

-06 Itemboxes
Most of the 06 itemboxes have been imported, this includes 5,10,20 ring, invincibility, gauge up capsules and more can be located in various stages, not only you can lock-on to them just like 06, they also came with recreated particle effects!

-Character Specific Dialogs
Dialogs will be changed base on what character you are playing, if you play as Sonic+Elise in "Sonic 06 Definitive Experience" mod in Tropical Jungle, different dialogs will be played!

-Walking NPCs
There were no existing ways to make objects follow a path in Sonic Generations, Soleanna HUB World used to only have static NPCs, but with code injection, walking NPCs are now possible and made the HUB World more lively!

------------------------------------------------------------
Sonic 06 Definitive Experience (character & physics mod):
------------------------------------------------------------
This mod fully supports the latest version of "Sonic 06 Definitive Experience", you will be able to not only play with character models from 06, but also change the gameplay into 06 style, and also use recreated movesets from 06!

Download it here:
https://gamebanana.com/mods/250121

------------------------------------------------------------
Switching UI Language:
------------------------------------------------------------
Switching voice over in game does NOT change the subtitle language, to do that you have the change the locale in registry of your game, via Steam or manually if prior doesn't work.

Changing language via Steam:
1. Log into your Steam account
2. Right click on a game from the Steam game library and choose Properties.
3. Go to the Language tab
4. Select the language you wish to use from the drop-down menu
5. Click OK

If the above doesn't work, try this:
1. Press Win+R and run "regedit"
2. Goto "HKEY_LOCAL_MACHINE\SOFTWARE\SEGA\Sonic Generations", location might vary for users, it could also locate at "HKEY_LOCAL_MACHINE\SOFTWARE\Wow6432Node\SEGA\Sonic Generations", search for "Sonic Generations" or the directory of you Geneations folder "C:\xxxx\xxxx\sonic generations" if you can't find it
3. Double click and change the code in the "locale" language codes:

"1033" for "English"
"1036" for "French"
"1031" for "German"
"1040" for "Italian"
"3082" for "Spanish"
"0411" for "Japanese"

------------------------------------------------------------
Known Issues
------------------------------------------------------------
-In Crisis City part 2 where you grind rails, sometimes if you switch rail you might fall under the rails, the is due the the paths aren't perfectly in parallel in the original design of Crisis City
-When continuing from a save, it can take about 7 seconds to start transitioning, this is harmless but can feel weird if not known beforehand

------------------------------------------------------------
Changelog
------------------------------------------------------------
v1.2
-Fixed HUB world load times

v1.1
-Made "Direct3D 9 Ex" mod mandatory for this mod
-Enforced "Sonic 06 Definitive Experience" mod priority
-Stage SceneEffect adjustment
-Minor typo fix

v1.0
-Initial release

------------------------------------------------------------
Credits
------------------------------------------------------------
brianuuu (brianuuuSonic)
-Main mod developer
-All stages terrain, splines, layout designs
-06 objects and animations
-Omochao removal
-Stage object physics
-Story sequence hacking
-06 particle effects recreation
-DLL mod codes

joeylaw123
-Main mod developer
-Creator of Tropical Jungle Part 1&2
-Stage object physics

samothethief
-Creator of SonicGlvl

Dude
-Spline Exporter

Skyth
-Tools and various help

ItsHelias94
-Soleanna HUB GIA
-Tropical Jungle, Kingdom Valley GIA

UltimateDarkman
-Mephlies animation
-Various rigging fix
-Sliver animation in Kingdom Valley
-Background dolphin animations in Wave Ocean
-Background eagle animations in Kingdom Valley
-06 springs

Mario Tainaka
-Stage sound effects
-Japanese voice clips
-Stage BGM
-Cutscene fixing and encoding
-Various sound encoding

Goalringmod27
-Wave Ocean GIA

TiManXD
-06 dashpad & rainbow ring
-Mod banner
-Mod introduction cilp

Paraxade0
-UV-anim script
-06 path import script
-Whale model in Wave Ocean

Zoney (TwlightZoney)
-Chaos Drive/Light Core models & materials

sonimayo27
-Beta testing
-Japanese subtitle translation & proof-reading

Kitzu
-Stage SceneEffect adjustment

Sajid
-Project funding

Crash5band
-Creator of Glitter Studio (particle effect editor)

sobatsuyu100, JohnTB, Double S 124, Playcore22, Brolijah
-Beta testing

SonicJGB
-STH2006 cutscenes recording

Mefiresu
-06 CSB Tool

Arcieo
-Decomplied lua script from XBOX360 version

BoomBoomFP
-E123-Omega replace Vector model

Somecallmejohnny
-Michael Scott reaction to Elise's kiss idea