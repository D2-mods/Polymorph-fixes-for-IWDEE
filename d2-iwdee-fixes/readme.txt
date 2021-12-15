Polymorph (and other) fixes for IWD:EE
GitHub: https://github.com/D2-mods/Polymorph-fixes-for-IWDEE 
Installs on: IWD:EE (tested on v2.5 and v2.6)


==================================================
WHAT THIS MOD DOES
==================================================
This is a small fix/tweak mod for IWD:EE, mainly dealing with polymorph-related things. Fixes some stats and edits descriptions of Shapechange forms to all share the same layout. The descriptions for fire/earth elemental now also list the correct resistances (identical to Druid forms). Also makes minor changes to the Mind Flayer's Psionic Blast.


==================================================
INSTALL INFO
==================================================
Extract to game folder and run the setup to install or uninstall. I'm not familiar with Mac/Linux, but installing should be the same as other mods (mod packages are cross-platform). The main fixes component assumes that you are using vanilla Shapechange forms, so by its nature, it will conflict with any mod that alters these forms.

Components:
1. Polymorph fixes for IWD:EE
2. Patch for nymph.BCS (fixes crash with EEex)
3. Make movement rate bonuses of polymorph forms more consistent
4. Increase movement speed of Winter Wolf and Polar Bear forms

All components can be installed independently and in any order. The movement rate components should be compatible with anything, as long as file names are unchanged.


==================================================
MAIN COMPONENT
==================================================
Polymorph Self
- removed Haste from Winter Wolf, Boring Beetle, and Polar Bear

Shapechange (all changed to match descriptions)
- Giant Troll Strength changed from 18 to 18/00
- Water Elemental weapon damage changed from 1d8 to 4d8

Text edits:
- all Shapechange forms (consistent layouts and accurate stats)

Psionic Blast
- added missing description for v2.5
- uses IWDEE v2.6 version as a base, with a few changes:
1. Stun duration changed to 5 rounds (from 10) to match description
2. Ability regenerates when used (this just skips the extra step of needing to re-shapechange into a Mind Flayer if you wanted to use Psionic Blast more than once)
3. Added back the orb thing over a stunned creature


==================================================
CREDITS
==================================================
Coding, Testing: Dan_P

Tools and Resources used:
- WeiDU v249 https://github.com/WeiDUorg/weidu
- NearInfinity v2.2-20210501 https://github.com/Argent77/NearInfinity
- Notepad++ https://notepad-plus-plus.org/
- Git Bash https://git-scm.com/downloads
- Infinity Auto Packager https://github.com/InfinityTools/InfinityAutoPackager
- IESDP https://gibberlings3.github.io/iesdp/index.htm


==================================================
VERSION HISTORY
==================================================
v1.5
- added options for making movement rate bonuses of shapeshifts more consistent
- added an option for faster movement speed for the Winter Wolf and Polar Bear forms

v1.4
- added check for script from Better IWD Pregen mod (nymph.BCS patches will be skipped)

v1.3
- added a fix for nymph.BCS (Call Woodland Beings) crashing with EEex (v0.8.7-alpha)

v1.0
-initial release