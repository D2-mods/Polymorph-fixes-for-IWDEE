Polymorph (and other) fixes for IWD:EE

GitHub: https://github.com/D2-mods/Polymorph-fixes-for-IWDEE 
Download: https://github.com/D2-mods/Polymorph-fixes-for-IWDEE/releases
Installs on: IWD:EE (tested on v2.5 and v2.6)
Languages: English, Russian (yota13)


This is a small fix/tweak mod for IWD:EE, mainly dealing with polymorph-related things. The other components are fixes or tweaks for random stuff I noticed.

--

Components:
1. Polymorph fixes for IWD:EE
2. Patch for nymph.BCS (fixes crash with EEex)
3. Shapeshift movement bonuses bypass Free Action
4. Increase movement speed of Winter Wolf and Polar Bear forms
5. Uncap Crippling Strike (capped at -7 in v2.5 and v2.6.6)
6. Patch shortbows to use shortbow visuals (as in classic IWD)
7. Object.ids - Add identifiers if missing (for scripting)
8. Minor AI tweak (enemies and invisible PCs)

Additional info:
- All components can be installed independently and in any order.
- Component 1 assumes you are using vanilla Shapechange forms. Install before mods that change creature stats (ex. Improved HoF).
- This mod shares some components with the Better IWD Pregen mod. If similar components are installed, whichever is installed last will be used (no issues or duplicated effects).

--

Polymorph fixes (component 1)

NOTE: Skipped if EE Fixpack is installed.

Polymorph Self
- Removed permanent Haste from Winter Wolf, Boring Beetle, and Polar Bear.

Shapechange
- Giant Troll Strength changed from 18 to 18/00 to match description.
- Water Elemental weapon damage changed from 1d8 to 4d8 (same as Druid form).
- Text edits: Consistent layouts and accurate stats.

Psionic Blast (mind flayer ability)
- Added missing description (for IWDEE v2.5).
- Stun duration changed to 5 rounds to match description.
- Can be used at will, while in mind flayer form.
- The rest of the effects are based on the v2.6 version.

--

Minor AI tweak (enemies and invisible PCs)

Some enemy groups in the unmodded game will walk to and surround Player1 (first character created) if the entire party is invisible or offscreen. This prevents Player1 from moving.

This tweak changes it so that these enemies will instead walk or stand around randomly. For certain battles, enemies will still walk towards the party, but they won't surround Player1 anymore.

This will only patch official scripts included with the game.

--

Modder: Dan_P

Russian translation: yota13

Tools and Resources used:
- WeiDU (https://github.com/WeiDUorg/weidu)
- NearInfinity (https://github.com/Argent77/NearInfinity)
- Notepad++ (https://notepad-plus-plus.org/)
- Git Bash (https://git-scm.com/downloads)
- WeiDU Mod Packager (https://github.com/InfinityTools/WeiduModPackager)
- IESDP (https://gibberlings3.github.io/iesdp/main.htm)
- WeiDU readme (https://weidu.org/~thebigg/README-WeiDU.html)

Used for older releases (replaced by WeiDU Mod Packager):
- Infinity Auto Packager (https://github.com/InfinityTools/InfinityAutoPackager)
- 7-Zip (https://www.7-zip.org/)

--

Updates:

v2.5
- now fixes #BONECIR.SPL if not already fixed. This is done from any component.
- improved Object.ids patch. Now checks missing entries individually and uses a better method for patching. NOTE: This is safe to install after any other mod that adds missing entries to object.ids (ex. EE Fixpack). Object identifiers will not be added if already in the file.

v2.4
- updated various install files.
- Psionic Blast: Spinny orb visual now only lasts a couple seconds, instead of the full stun duration.
- Polymorph component now also patches Free Action spell/rings and Chaotic Commands to make sure they block all stun-related strings (they don't in the unmodded game).

v2.3
- Object.ids patch: This will no longer edit typos. This is in case other mods use the typo versions. Identifiers with corrected spelling will now be added to the bottom of the file instead.

v2.2
- Skips the following components if EE Fixpack is installed:
	- Polymorph fixes
	- Patch for nymph.BCS
	- Uncap Crippling Strike
	- Object.ids fixes
- The current EE Fixpack repo already includes these in some form.
- Cleaned up possible harmless weidu warning messages.
- Slightly reorganized TRA files.

v2.1
- changed backup folder to weidu_external

v2.0
- added component: Minor AI tweak (enemies and invisible PCs). 

Info:
Some enemy groups in the unmodded game will walk to and surround Player1 (first character created) if the entire party is invisible or offscreen. This tweak changes it so that these enemies will instead walk or stand around randomly. For certain battles, enemies will still walk towards the party, but they shouldn't all surround Player1 anymore (preventing them from moving).

NOTE: I've tested this in a few places (ex. Severed Hand), but I haven't done a full playthrough yet. I don't think there should be issues, but I haven't checked every enemy group affected by this component.


v1.9.4
- added component to fix issues with the object.IDS file (typos, missing lines)

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