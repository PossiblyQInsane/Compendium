---
Name: "[[Homunculus Servant]]"
Spell Level: Level 2
School: Conjuration
Components: V, S, M
Classes: Artificer
Special: R, M
Source:
  - "Eberron: Forge of the Artificer"
tags:
  - Official
---
_Level 2 Conjuration ([[Artificer|Artificer]])_
***
**Casting Time:** 1 hour or [[Ritual]]  
**Range:** 10 feet  
**Components:** V, S, M (a gem worth 100+ GP)  
**Duration:** Instantaneous
***
You summon a special homunculus in an unoccupied space within range. This creature uses the **Homunculus Servant** stat block. If you already have a homunculus from this spell, the homunculus is replaced by the new one. You determine the homunculus’s appearance, such as a mechanical-looking bird, winged vial, or miniature animate cauldron.

_**Combat.**_ The homunculus is an ally to you and your allies. In combat, it shares your [[Initiative]] count, but it takes its turn immediately after yours. It obeys your commands (no action required by you). If you don’t issue any, it takes the [[Dodge]] action and uses its movement to avoid danger.

_**Using a Higher-Level Spell Slot.**_ Use the spell slot’s level for the spell’s level in the stat block.

```statblock
layout: Basic 5e 2025 Layout
name: Homunculus Servant
size: Tiny
type: Construct
alignment: Neutral<br>

ac: 13<br>

hp: 5 + 5 per spell level (the homunculus has a number of Hit Dice [d4s] equal to the spell’s level)<br>

speed: 20 ft., Fly 30 ft.
stats: [4, 15, 12, 10, 10, 7]
damage_immunities: Poison; [[Exhaustion]], [[Poisoned]]
senses: [[Darkvision|Darkvision]] 60 ft.; Passive Perception 10
languages: Telepathy 1 mile (works only with you)
cr: None (XP 0; PB equals your Proficiency Bonus)
traits:
  - name: Evasion.
    desc: If the homunculus is subjected to an effect that allows it to make a Dexterity saving throw to take only half damage, the homunculus instead takes no damage if it succeeds on the save and only half damage if it fails. It can’t use this trait if it has the [[Incapacitated]] condition.
  - name: Magic Bond.
    desc: Add the spell’s level to any ability check or saving throw the homunculus makes.
actions:
  - name: Force Strike.
    desc: _Melee or Ranged Attack Roll:_ Bonus equals your spell attack modifier, reach 5 ft. or range 30 ft. _Hit:_ 1d6 plus the spell’s level Force damage.
reactions:
  - name: Channel Magic.
    desc: _Trigger:_ You cast a spell that has a range of touch while the homunculus is within 120 feet of you. _Response:_ The homunculus delivers the spell through its touch.
```
