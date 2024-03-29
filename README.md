# Polymorph (and other) fixes for IWD:EE
Download: https://github.com/D2-mods/Polymorph-fixes-for-IWDEE/releases  
Installs on: IWD:EE (tested on v2.5 and v2.6)
Languages: English, Russian (yota13)


#### Components:
1. Polymorph fixes for IWD:EE
2. Patch for nymph.BCS (fixes crash with EEex)
3. Should shapeshift movement bonuses bypass Free Action?
4. Increase movement speed of Winter Wolf and Polar Bear forms
5. Uncap Crippling Strike (capped at -7 in v2.5 and v2.6.6)
6. Patch shortbows to use shortbow visuals (as in classic IWD)
7. Object.ids - Add identifiers if missing (for scripting)
8. Minor AI tweak (enemies and invisible PCs)


#### Install info:
- All components can be installed independently and in any order.
- Component 1 assumes you are using vanilla Shapechange forms. Install before mods that change creature stats (ex. Improved HoF)
- Components 3-6 will not conflict with similar components in the Better IWD Pregen mod.


#### Additional info:

<details>
  <summary>Polymorph fixes (component 1)</summary>
  
---

NOTE: Skipped if EE Fixpack is installed.

#### Polymorph Self
- removed permanent Haste from Winter Wolf, Boring Beetle, and Polar Bear

#### Shapechange
- Giant Troll Strength changed from 18 to 18/00 to match description
- Water Elemental weapon damage changed from 1d8 to 4d8 (same as Druid form)

#### Text edits (Shapechange):
- Consistent layouts and accurate stats

#### Psionic Blast
- Added missing description in v2.5 (when right-clicking the icon)
- Uses the v2.6 version as a base, with a few changes:
1. Stun duration changed to 5 rounds (from 10) to match description
2. Ability regenerates when used
3. Added back the orb animation over a stunned creature

---

</details>


<details>
  <summary>Minor AI tweak (enemies and invisible PCs)</summary>
  
---

#### Info:
  
Some enemy groups in the unmodded game will walk to and surround Player1 (first character created) if the entire party is invisible or offscreen. This prevents Player1 from moving.

This tweak changes it so that these enemies will instead walk or stand around randomly. For certain battles, enemies will still walk towards the party, but they won't surround Player1 anymore.

This will only patch official scripts included with the game.

---

</details>