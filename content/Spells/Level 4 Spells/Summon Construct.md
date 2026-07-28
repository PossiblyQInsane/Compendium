---
Name: "[[Summon Construct]]"
Spell Level: Level 4
School: Conjuration
Components: V, S, M
Classes: Artificer, Wizard
Special: C, M
Source:
  - Player's Handbook (5.5e)
tags:
  - Official
---
_Level 4 Conjuration ([[Artificer|Artificer]], [[Wizard]])_
***
**Casting Time:** Action  
**Range:** 90 feet  
**Components:** V, S, M (a lockbox worth 400+ GP)  
**Duration:** [[Concentration]], up to 1 hour
***
You call forth the spirit of a Construct. It manifests in an unoccupied space that you can see within range and uses the **Construct Spirit** stat block. When you cast the spell, choose a material: Clay, Metal, or Stone. The creature resembles an animate statue (you determine the appearance) made of the chosen material, which determines certain details in its stat block. The creature disappears when it drops to 0 [[Hit Points]] or when the spell ends.

The creature is an ally to you and your allies. In combat, the creature shares your [[Initiative count]], but it takes its turn immediately after yours. It obeys your verbal commands (no action required by you). If you don’t issue any, it takes the [[Dodge]] action and uses its movement to avoid danger.

_**Using a Higher-Level Spell Slot.**_ Use the spell slot’s level for the spell’s level in the stat block.

```statblock
layout: Basic 5e 2025 Layout
name: Construct Spirit
size: Medium
type: Construct
alignment: Neutral
ac: 13 + the spell’s level
hp: 40 + 15 for each spell level above 4
speed: 30 ft.
stats: [18, 10, 18, 14, 11, 5]
damage_resistances: Poison
damage_immunities: [[Charmed]], [[Exhaustion]], [[Frightened]], [[Paralyzed]], [[Poisoned]]
senses: [[Darkvision]] 60 ft.; Passive Perception 10
languages: Understands the languages you know
cr: None (XP 0; PB equals your Proficiency Bonus)
traits:
  - name: Heated Body (Metal Only)
    desc: A creature that hits the spirit with a melee attack or that starts its turn in a grapple with the spirit takes 1d10 Fire damage.
  - name: Stony Lethargy (Stone Only)
    desc: When a creature starts its turn within 10 feet of the spirit, the spirit can target it with magical energy if the spirit can see it. _Wisdom Saving Throw:_ DC equals your spell save DC, the target. _Failure:_ Until the start of its next turn, the target can’t make [[Opportunity Attack|Oppurtunity Attacks]], and its [[Speed]] is halved.
actions:
  - name: Multiattack
    desc: The spirit makes a number of Slam attacks equal to half this spell’s level (round down).
  - name: Slam
    desc: _Melee Attack Roll:_ Bonus equals your spell attack modifier, reach 5 ft. _Hit:_ 1d8 + 4 + the spell’s level Bludgeoning damage.
reactions:
  - name: Berserk Lashing (Clay Only)
    desc: _Trigger:_ The spirit takes damage from a creature. _Response:_ The spirit makes a Slam attack against that creature if possible, or the spirit moves up to half its Speed toward that creature without provoking [[Opportunity Attack|Oppurtunity Attacks]].
```

