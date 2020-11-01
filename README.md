# BOPPER TING aka #OptisDontExist by fri-end
**Most code is not mine. Most of the code is others and I have just combined it all into one project. I have tried to include a reference to all code that I have used.**

Feeling kind of cute. Might release. Might not.

/shrug

# BASE: CSGOSimple
## Repositories:  
- Gitlab: https://gitlab.com/spirt/csgosimple
- Github: https://github.com/spirthack/csgosimple

# INSTALLATION
- Download #OptisDontExist
- Download injector (Such as CSGhost from https://www.unknowncheats.me/forum/cs-go-releases/408519-csghost-v2-trusted-bypassing-injector.html)
- Open game
- Run injector
    - Inject dll
- Use the "F5" key to open and hide the menu

# CHANGE LOG
## Version 0.4/0.45:
- Change color scheme
- [REDACTED]

## Version 0.5 (CURRENT BUILD):
- Added start speed slider (240-290 u/s)

- Replaced hardcoded mouse sensitivity and m_yaw with convars

## Version 0.6:
- Add keybinds... nulls, shsw, sideways key swap, and w key prevention
- Add slider to add delay to strafe (0 ticks - 5 ticks) and randomize "perfect" strafes 
- Add spectator list (Osiris???)
- Add sound modifier (Osiris???) (Remove things such as chicken noise or map music)

- Modified slider values to read from left to right instead of right to left.
- Modify auto bhop... simulate more jump presses (mimic actual scroll) + randomized number of jumps
- Modify auto strafe... Something else instead of sidemove (to be more "legit")
- Modify optimizer... stop opimizing if little mouse movement
- Modify optimizer... stop optimizing if too much mouse movement... such as past ideal strafe

## Version 0.7:
- Add bash 2 style deviation recorder + warn player function
- Add optional name/clantag changer
- Add toggle/press to hold key option
- Add option to remove pause between strafes (always moving left or right)

- Modify optimizer... different ideal strafe calculation

## Version 0.8:
- Support for other styles such as sideways
- Fake backwards and fake sideways
    - just add 180 or so to cmd->viewangles.y and when enabling / disabling lerp the added angle so it looks legit?
    - https://www.unknowncheats.me/forum/2654670-post2.html
    - https://github.com/McSwaggens/DingoSquad/blob/master/src/AntiAim.cpp

## Version 0.9:
- Movement recorder

## Version 1.0:
- Complete GUI revamp
- Remove junk code such as unused csgo offsets

# Miscellanous links:
- [STEAM ID FINDER](https://steamid.io/)

- [Source smallest normalize function](https://www.unknowncheats.me/forum/counterstrike-global-offensive/166415-normalize-function.html)
- [GET_CVAR_MOUSE_SENSITIVITY](https://www.unknowncheats.me/forum/2288413-post2.html)
- [Secure Salted Password Hashing - How to do it Properly](https://crackstation.net/hashing-security.htm)

## BHOP CODE
- [UnKnoWnCheaTs - Multiplayer Game Hacks and Cheats - View Single Post - Request Make this Simple Bhop to SMAC Proof!](https://www.unknowncheats.me/forum/1691836-post2.html)
- [SMAC proof Bhop by tirziz · Pull Request #450 · danielkrupinski/Osiris · GitHub](https://github.com/danielkrupinski/Osiris/pull/450/commits/59a46451abf749cc3ce6ec1c3edc08b1fa92ee8b)
- [KiHop/bhop.cpp at master · Kiyumi/KiHop · GitHub](https://github.com/Kiyumi/KiHop/blob/master/src/bhop.cpp)
- [How to make a BUNNYHOP! CS:GO Cheat Series! (Episode 3) - YouTube](https://www.youtube.com/watch?v=Fq3eaGYUvNs)

## STRAFE CODE
- [STRAFE OPTI CODE](https://www.unknowncheats.me/forum/2880560-post25.html)
- [Release Proper autobhop, 100% gain strafer](https://www.unknowncheats.me/forum/counterstrike-global-offensive/257614-proper-autobhop-100-gain-strafer.html)
- [PZ_CSGO_CHEAT/Misc.cpp at master · BlackSickness/PZ_CSGO_CHEAT · GitHub](https://github.com/BlackSickness/PZ_CSGO_CHEAT/blob/master/Misc.cpp#L380)
- [Source proper auto strafer](https://www.unknowncheats.me/forum/counterstrike-global-offensive/168189-proper-auto-strafer.html)
- [hlstrafe/hlstrafe.cpp at master · HLTAS/hlstrafe](https://github.com/HLTAS/hlstrafe/blob/master/src/hlstrafe.cpp#L16)
- [Source Multidirectional Autostrafer](https://www.unknowncheats.me/forum/counterstrike-global-offensive/356497-multidirectional-autostrafer.html)
- [Source Multidirectional Autostrafer](https://www.unknowncheats.me/forum/2582287-post1.html)
- [FAST AUTOSTAFE](https://www.unknowncheats.me/forum/2297071-post1.html)
- [AUTO STRAFE CODE FOR OPTI](https://www.unknowncheats.me/wiki/Counter_Strike_Global_Offensive:Proper_auto-strafer)
- [Coding Basic Auto Strafe](https://www.unknowncheats.me/forum/counterstrike-global-offensive/144026-basic-auto-strafe.html)
- [Kappahack/autostrafe.rs at master · rwittek/Kappahack · GitHub](https://github.com/rwittek/Kappahack/blob/master/src/autostrafe.rs)

## SOURCE SDK CODE/THEORY
- [source-sdk-2013/gamemovement.cpp at 55ed12f8d1eb6887d348be03aee5573d44177ffb · ValveSoftware/source-sdk-2013 · GitHub](https://github.com/ValveSoftware/source-sdk-2013/blob/55ed12f8d1eb6887d348be03aee5573d44177ffb/sp/src/game/shared/gamemovement.cpp#L1750-L1799)
- [QW physics air - QWiki](https://www.quakeworld.nu/wiki/QW_physics_air)
- [F3quake - Article: Strafing Theory](https://web.archive.org/web/20141224180047/funender.com/quake/articles/strafing_theory.html)
- [HOW CHEATS ARE DETECTED](https://github.com/shavitush/bhoptimer/issues/411)
- [Strafing Theory by injx](https://dimit.me/blog/2017/08/08/defrag-strafe-theory/)
- [airacceleration affects maximum vel](https://www.unknowncheats.me/forum/1394545-post8.html)
- [RUMOUR - HOW OPTIS WORK](https://www.unknowncheats.me/forum/1717007-post8.html)
- [MENU CODE](https://github.com/spirthack/CSGOSimple/blob/master/CSGOSimple/menu.cpp)
- [tastools/strafemath.cpp at master · Matherunner/tastools · GitHub](https://github.com/Matherunner/tastools/blob/master/injectlib/strafemath.cpp)
- [hlstrafe/hlstrafe.cpp at master · HLTAS/hlstrafe · GitHub](https://github.com/HLTAS/hlstrafe/blob/master/src/hlstrafe.cpp#L11)
- [TAS](https://github.com/momentum-mod/game/blob/f4f63671acfc244c6f32b8182206c946fbaee5ea/mp/src/game/shared/momentum/mom_gamemovement.cpp#L1414)
- [SSJ CODE](https://github.com/neko-pm/ssj/blob/master/scripting/ssj.sp)
- [STRAFE TRAINER CODE](https://github.com/PaxPlay/bhop-strafe-trainer/blob/master/scripting/strafe_trainer.sp)

## FAKE ANGLES
- [Fake angles](https://www.unknowncheats.me/forum/1672167-post11.html)
- [UnKnoWnCheaTs - Multiplayer Game Hacks and Cheats - View Single Post - Help "fake backwards" camera](https://www.unknowncheats.me/forum/2656939-post13.html)

## SPECTATORS
- [Source Spectators List](https://www.unknowncheats.me/forum/counterstrike-global-offensive/226226-spectators-list.html)
- [Get spectators](https://www.unknowncheats.me/forum/1763255-post4.html)

## BASES
- [GitHub - danielkrupinski/Osiris: Free open-source game cheat for Counter-Strike: Global Offensive, written in modern C++. GUI powered by imgui.](https://github.com/danielkrupinski/Osiris)

## RECORDERS
- [Input recording & re-recording. | aixxe](https://aixxe.net/2017/04/source-input-recorder)
- [Coding Movement Record](https://www.unknowncheats.me/forum/counterstrike-source/102831-movement-record.html)
- [Source Movement recording](https://www.unknowncheats.me/forum/counterstrike-global-offensive/362788-movement-recording.html)

## KEY PRESS SIMULATION
- [Question How to simulate up-arrow key in the game?](https://www.unknowncheats.me/forum/grand-theft-auto-v/258672-simulate-arrow-key-game.html)
- [winapi - SendInput() not equal to pressing key manually on keyboard in C++? - Stack Overflow](https://stackoverflow.com/questions/18647053/sendinput-not-equal-to-pressing-key-manually-on-keyboard-in-c)
- [The PC keyboard Scan Codes](http://www.philipstorr.id.au/pcbook/book3/scancode.htm)
- [c++ win32 Simulate Keypress with DirectInput - Stack Overflow](https://stackoverflow.com/questions/7320424/c-win32-simulate-keypress-with-directinput)