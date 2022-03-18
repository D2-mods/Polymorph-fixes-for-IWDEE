Polymorph (and other) fixes for IWD:EE
GitHub: https://github.com/D2-mods/Polymorph-fixes-for-IWDEE 
Installs on: IWD:EE (tested on v2.5 and v2.6)
Languages: English, Russian (yota13)


==================================================
WHAT THIS MOD DOES
==================================================
This is a small fix/tweak mod for IWD:EE, mainly dealing with polymorph-related things.


==================================================
INSTALL INFO
==================================================
Extract to game folder and run the setup to install or uninstall. I'm not familiar with Mac/Linux, but installing should be the same as other mods (mod packages are cross-platform).

Components:
1. Polymorph fixes for IWD:EE
2. Patch for nymph.BCS (fixes crash with EEex)
3. Make movement rate bonuses of polymorph forms more consistent
4. Increase movement speed of Winter Wolf and Polar Bear forms
5. Uncap Crippling Strike (capped at -7 in v2.5 and v2.6.6)
6. Patch shortbows to use shortbow visuals (as in classic IWD)

All components can be installed independently and in any order.
The main fixes component assumes you are using vanilla Shapechange forms. Should still be safe to install before revision or overhaul mods (ex. Improved HoF mod).


==================================================
Polymorph fixes (component 1)
==================================================
Polymorph Self
- removed permanent Haste from Winter Wolf, Boring Beetle, and Polar Bear

Shapechange
- Giant Troll Strength changed from 18 to 18/00 to match description
- Water Elemental weapon damage changed from 1d8 to 4d8 (same as Druid form)

Text edits:
- all Shapechange forms given consistent layouts and accurate stats

Psionic Blast
- added missing description in v2.5 (when right-clicking the icon)
- uses the v2.6 version as a base, with a few changes:
1. Stun duration changed to 5 rounds (from 10) to match description
2. Ability regenerates when used (this just skips the extra step of needing to re-shapechange into a Mind Flayer if you wanted to use Psionic Blast more than once)
3. Added back the orb animation over a stunned creature


==================================================
CREDITS
==================================================
Coding, Testing: Dan_P

Russian translation: yota13

Tools and Resources used:
- WeiDU v249 https://github.com/WeiDUorg/weidu
- NearInfinity v2.2-20211218 https://github.com/Argent77/NearInfinity
- Notepad++ https://notepad-plus-plus.org/
- Git Bash https://git-scm.com/downloads
- Infinity Auto Packager https://github.com/InfinityTools/InfinityAutoPackager
- IESDP https://gibberlings3.github.io/iesdp/index.htm


==================================================
VERSION HISTORY
==================================================
v1.9.3
- improved the shortbow patch

v1.9.2
- added a patch for shortbows to use shortbow visuals (as in classic IWD)

v1.9.1
- Minor update. Adds some additional checks for installing the Crippling Strike component.

v1.9
- added a fix for Crippling Strike being capped at -7 (in both IWD:EE v2.5 and v2.6.6). The Record screen and dialogue box could show lower numbers, but the effect never went past -7.

v1.8
- added Russian translation by yota13 from https://arcanecoast.ru/

v1.7
- fixed a regression added by the last update; component 1 (fixes) should no longer overwrite component 4 (faster wolf/bear) if installed after

v1.6
- Component 3 (movement tweak) will also update the IWDEE v2.5 polymorphs to use the stacking multiplier (regardless of which option is chosen). This was already the case in v2.6.
- Component 4 (faster wolf/bear forms) now updates description text and adds a portrait icon. It will also now increase speed of the Brown Bear and Black Bear polymorphs.
- updated install to to handle patching previously modified files better (i.e. avoid creating duplicate effects)

v1.5
- added options for making movement rate bonuses of shapeshifts more consistent
- added an option for faster movement speed for the Winter Wolf and Polar Bear forms

v1.4
- added check for script from Better IWD Pregen mod (nymph.BCS patches will be skipped)

v1.3
- added a fix for nymph.BCS (Call Woodland Beings) crashing with EEex (v0.8.7-alpha)

v1.0
-initial release