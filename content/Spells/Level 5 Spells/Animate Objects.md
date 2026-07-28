---
Name: "[[Animate Objects]]"
Spell Level: Level 5
School: Transmutation
Components: V, S
Classes: Artificer, Bard, Sorcerer, Wizard
Special: C
Source:
  - Player's Handbook (5.5e)
tags:
  - Official
---
_Level 5 Transmutation ([[Artificer|Artificer]], [[Bard]], [[Sorcerer]], [[Wizard]])_
***
**Casting Time:** Action  
**Range:** 120 feet  
**Components:** V, S  
**Duration:** [[Concentration]], up to 1 minute
***
Objects animate at your command. Choose a number of nonmagical objects within range that aren’t being worn or carried, aren’t fixed to a surface, and aren’t Gargantuan. The maximum number of objects is equal to your spellcasting ability modifier; for this number, a Medium or smaller target counts as one object, a Large target counts as two, and a Huge target counts as three.

Each target animates, sprouts legs, and becomes a Construct that uses the **Animated Object** stat block; this creature is under your control until the spell ends or until it is reduced to 0 [[Hit Points]]. Each creature you make with this spell is an ally to you and your allies. In combat, it shares your [[Initiative]] count and takes its turn immediately after yours.

Until the spell ends, you can take a [[Bonus Action]] to mentally command any creature you made with this spell if the creature is within 500 feet of you (if you control multiple creatures, you can command any of them at the same time, issuing the same command to each one). If you issue no commands, the creature takes the [[Dodge]] action and moves only to avoid harm. When the creature drops to 0 [[Hit Points]], it reverts to its object form, and any remaining damage carries over to that form.

_**Using a Higher-Level Spell Slot.**_ The creature’s Slam damage increases by 1d4 (Medium or smaller), 1d6 (Large), or 1d12 (Huge) for each spell slot level above 5.

```statblock
layout: Basic 5e 2025 Layout
name: Animated Object
size: Huge or Smaller
type: Construct
alignment: Unaligned
ac: 15
hp: 10 (Medium or smaller), 20 (Large), 40 (Huge)
speed: 30 ft.
stats: [16, 10, 10, 3, 3, 1]
damage_immunities: Poison, Psychic; [[Charmed]], [[Exhaustion]], [[Frightened]], [[Paralyzed]], [[Poisoned]]
senses: [[Blindsight]] 30 ft.; Passive Perception 6
languages: Understands the languages you know
cr: None (XP 0; PB equals your Proficiency Bonus)
actions:
  - name: Slam
    desc: _Melee Attack Roll:_ Bonus equals your spell attack modifier, reach 5 ft. _Hit:_ Force damage equal to 1d4 + 3 (Medium or smaller), 2d6 + 3 + your spellcasting ability modifier (Large), or 2d12 + 3 + your spellcasting ability modifier (Huge).
```
