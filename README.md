# Polymorph (and other) fixes for IWD:EE

Download: https://github.com/D2-mods/Polymorph-fixes-for-IWDEE/releases  
Languages: English, Russian (yota13)

--

This is a small fix/tweak mod for Icewind Dale: Enhanced Edition. It was originally made to deal with polymorph-related things. The other components are fixes or tweaks for random stuff I noticed.

This mod is compatible with EE fixpack. Install this mod after EE fixpack. Some components will be skipped automatically.

--

### Components:
1. Polymorph fixes for IWD:EE
2. Patch for nymph.BCS (fixes crash with EEex)
3. Shapeshift movement bonuses bypass Free Action
4. Increase movement speed of IWD shapeshifts (EE and classic)
5. Uncap Crippling Strike (capped at -7 in v2.5 and v2.6.6)
6. Patch shortbows to use shortbow visuals (as with 1pp/BGEE)
7. Object.ids - Add identifiers if missing (for scripting)
8. Minor AI tweak (enemies and invisible PCs)
9. Set Join_Posse variable in Kuldahar if not already set (i.e. if you warped there)


### Install info:
- All components can be installed independently and in any order.
- Polymorph fixes should be installed before any mods that tweak spells or creatures.
- This mod shares some components with the [Better IWD Pregen](https://github.com/D2-mods/Better-IWD-Pregen) mod. If similar components are installed, whichever is installed last will be used (no issues or duplicated effects).


### Additional info:

<details>
  <summary>Polymorph fixes (component 1)</summary>
  
---

> Note: Skipped if EE Fixpack is installed.

**Polymorph Self**
- Removed permanent Haste from Winter Wolf, Boring Beetle, and Polar Bear.

**Shapechange**
- Giant Troll Strength changed from 18 to 18/00 to match description.
- Water Elemental weapon damage changed from 1d8 to 4d8 (same as Druid form).
- Text edits: Consistent layouts and accurate stats.

**Psionic Blast (mind flayer ability)**
- Added missing description (for IWDEE v2.5).
- Stun duration changed to 5 rounds to match description.
- Can be used at will, while in mind flayer form.
- The rest of the effects are based on the v2.6 version.

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