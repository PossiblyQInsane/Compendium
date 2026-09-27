---
publish: true
created: 2026-09-11T01:13:35.457-04:00
modified: 2026-09-27T18:07:01.587-04:00
published: 2026-09-27T18:07:01.587-04:00
Name: "[[Beast Master]]"
Parent Class: "[[Ranger]]"
Source: Player's Handbook 5.5e
Official: true
Edition: 5.5e
---

<div class="source">Player's Handbook 5.5e</div>

> [!caption|left ws-med]
> ![[Images/Beast Master.png]]

_Bond with a Primal Beast_

A Beast Master forms a mystical bond with a special animal, drawing on primal magic and a deep connection to the natural world.

### Level 3: Primal Companion

You magically summon a primal beast, which draws strength from your bond with nature. Choose its stat block: **Beast of the Land**, **Beast of the Sea**, or **Beast of the Sky**. You also determine the kind of animal it is, choosing a kind appropriate for the stat block. Whatever beast you choose, it bears primal markings indicating its supernatural origin.

The beast is [[Friendly]] to you and your allies and obeys your commands. It vanishes if you die.

**_The Beast in Combat._** In combat, the beast acts during your turn. It can move and use its [[Reaction]] on its own, but the only action it takes is the [[Dodge]] action unless you take a [[Bonus Action]] to command it to take an action in its stat block or some other action. You can also sacrifice one of your attacks when you take the [[Attack]] action to command the beast to take the Beast’s Strike action. If you have the [[Incapacitated]] condition, the beast acts on its own and isn’t limited to the Dodge action.

**_Restoring or Replacing the Beast._** If the beast has died within the last hour, you can take a [[Magic]] action to touch it and expend a spell slot. The beast returns to life after 1 minute with all its Hit Points restored.

Whenever you finish a [[Long Rest]], you can summon a different primal beast, which appears in an unoccupied space within 5 feet of you. You choose its stat block and appearance. If you already have a beast from this feature, the old one vanishes when the new one appears.

![[Images/Beast of the Land.statblockwizard.png]]

<!DOCTYPE html>

<html lang="en"><head><meta charset="UTF-8"><title>Beast of the Land - Stat Block</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=PT+Sans:ital,wght@0,400;0,700;1,400;1,700&display=swap" rel="stylesheet">
<style>
/* box-sizing + line-height are set explicitly so the card renders IDENTICALLY in
   the app (where Tailwind Preflight supplies border-box and the site supplies
   line-height:1.5) and in the standalone HTML/PNG export (which has neither). Do
   not remove these: without them the export card computes as content-box (wider,
   different wrapping) with line-height:normal (~16% tighter text), so the export
   no longer matches the on-screen preview. */
.flokisstatgen, .flokisstatgen *, .flokisstatgen *::before, .flokisstatgen *::after {
  box-sizing: border-box;
}
table, th, td {
  border: none !important;
  border-collapse: collapse;
}
.flokisstatgen {
  --flokisScreenborder: #600000;
  --flokisGrey: #696969;
  /* The var() fallback is load-bearing for export. This CSS ships in a style
     element INSIDE the card, so el.outerHTML carries it into the PNG's isolated
     SVG foreignObject and the standalone HTML file, where --font-pt-sans is not
     defined. Without the fallback, that reference is invalid at computed-value
     time and discards the WHOLE font-family (reverting it to serif), reflowing
     the export so it no longer matches the preview. The fallback keeps it valid.
     (Keep the less-than character out of this CSS: the PNG path parses it as
     SVG/XML, where a bare one inside the style element breaks parsing.) */
  font-family: var(--font-pt-sans, "PT Sans"), "PT Sans", Arial, Helvetica, sans-serif;
  color: #020202 !important;
  background-color: #f8f4f0;
  width: 173mm;
  padding: 0 7px 7px;
  clear: both;
  font-size: 0.8em;
  font-weight: 300;
  font-kerning: auto;
  line-height: 1.5;
  letter-spacing: 0.02em;
  border: 3px #bcbcbc double;
  border-radius: 6px;
  margin: 0 auto 4px;
}
.flokisstatgen-SingleColumn { min-width: 100px; width: 340px; }
.flokisstatgen-Content { position: relative; }
/* Two-column mode: multicol lives on an inner wrapper that excludes the header,
   so no column-span is ever needed (WebKit mis-fragments spanning elements,
   duplicating the header). Single-column mode uses no multicol at all. */
.flokisstatgen:not(.flokisstatgen-SingleColumn) .flokisstatgen-Columns {
  columns: 2;
  column-gap: 8mm;
}
.flokisstatgen-likeyword, .flokisstatgen-keyword, .flokisstatgen strong, .flokisstatgen b {
  font-weight: bold; letter-spacing: 0.02em;
}
.flokisstatgen-keyword { color: #000000; }
.flokisstatgen-keyword::after { content: "\0000a0"; }
.flokisstatgen-title {
  font-family: var(--font-pt-sans, "PT Sans"), "PT Sans", Arial, Helvetica, sans-serif;
  font-size: 1.7em; font-weight: bold; letter-spacing: 0; font-variant: small-caps;
  color: #922610; padding: 0; margin: 0; width: 100%;
  border-bottom: 1px var(--flokisScreenborder) solid;
}
.flokisstatgen-sizetypetagsalignment {
  font-style: italic; color: #8a7a6a; margin-top: 2px; margin-bottom: 3px; padding-bottom: 2px;
}
.flokisstatgen-core { color: #000000; }
.flokisstatgen-general, .flokisstatgen-general2, .flokisstatgen-general3 { break-inside: avoid; border: none; }
.flokisstatgen-general2 { width: 100%; display: flex; }
.flokisstatgen-general2 > * { flex: 1 1 50%; min-width: 0; }
.flokisstatgen-abilities {
  box-sizing: border-box; break-inside: avoid; display: flex; flex-direction: row;
  flex-wrap: nowrap; justify-content: space-between; gap: 12px; width: 100%;
  clear: both; border: none; font-size: 1.1em;
}
/* flex:1 1 0 + min-width:0 lets the two tables shrink to share the row; a bare
   flex:1 keeps min-width:auto, so the border-collapse tables stay at their
   content min-width and the pair + gap overflows the card's right edge. width:100%
   + table-layout:fixed gives fixed layout a definite basis so columns distribute
   within the shared width instead of forcing the table wider. */
.flokisstatgen-abilitiesblock {
  border-collapse: collapse; border-spacing: 0; margin: 2px 0;
  flex: 1 1 0; min-width: 0; width: 100%; table-layout: fixed; color: #000000;
}
.flokisstatgen-physicalabilities { background-color: #f0e8e0; }
.flokisstatgen-physicalmods { background-color: #e0ccc4; }
.flokisstatgen-mentalabilities { background-color: #d8d8d0; }
.flokisstatgen-mentalmods { background-color: #ccc4c8; }
.flokisstatgen-abilitiesblock th {
  font-size: 1em; font-weight: lighter; text-transform: lowercase; font-variant: small-caps;
  text-align: right; padding: 2px 5px; line-height: 1.3; color: var(--flokisGrey);
}
.flokisstatgen-abilitiesblock td { padding: 4px 5px; line-height: 1.4; color: #000000; }
.flokisstatgen-ability { text-align: center; }
.flokisstatgen-abilityname {
  font-weight: bold; text-transform: uppercase; font-size: 0.85em; letter-spacing: 0.05em;
  text-align: left; padding-left: 3px; width: 1.5em;
}
.flokisstatgen-abilityscore, .flokisstatgen-abilitymodifier, .flokisstatgen-abilitysave {
  text-align: right; padding-right: 3px; width: 1.5em;
}
.flokisstatgen-features { border: none; margin-bottom: 2px; break-inside: avoid; }
.flokisstatgen-feature { text-indent: -1em; padding-left: 1em; margin-top: 1px; margin-bottom: 2px; }
.flokisstatgen-skill { color: #000000; }
.flokisstatgen-cr { margin-right: 3px !important; }
.flokisstatgen-sectionheader {
  color: #500000; text-transform: capitalize; font-size: 1.4em; letter-spacing: 0.02em;
  break-inside: avoid; width: 100%; margin-top: 10px; margin-bottom: 1px;
  border-bottom: 1px var(--flokisScreenborder) solid;
}
.flokisstatgen-sectionheader + .flokisstatgen-line { margin-top: 2px; }
.flokisstatgen-line { margin-top: 5px; margin-bottom: 2px; }
.flokisstatgen-line + .flokisstatgen-text { text-indent: 1em; margin-top: 2px; margin-bottom: 2px; }
.flokisstatgen-attacktype, .flokisstatgen-hit, .flokisstatgen-italic { font-style: italic; }
.flokisstatgen-hit::before { content: " "; }
.flokisstatgen-attacktype::after, .flokisstatgen-hit::after { content: "\0000a0"; }
.flokisstatgen-namedstring .flokisstatgen-keyword,
.flokisstatgen-attack .flokisstatgen-keyword,
.flokisstatgen-reaction .flokisstatgen-keyword { font-style: italic; }
.flokisstatgen-legendarytext { font-style: italic; color: var(--flokisGrey); }
.flokisstatgen-monster-image {
  float: right; max-width: 45%; max-height: 400px; margin: 5px 0 10px 15px;
  border: none; shape-outside: margin-box;
}
.flokisstatgen hr { margin: 2px 0; border: none; border-bottom: 1px var(--flokisScreenborder) solid; }
</style></head>
<body style="background:#f5f5f5;padding:20px;display:flex;justify-content:center;"><div class="flokisstatgen"><style>
/* box-sizing + line-height are set explicitly so the card renders IDENTICALLY in
   the app (where Tailwind Preflight supplies border-box and the site supplies
   line-height:1.5) and in the standalone HTML/PNG export (which has neither). Do
   not remove these: without them the export card computes as content-box (wider,
   different wrapping) with line-height:normal (~16% tighter text), so the export
   no longer matches the on-screen preview. */
.flokisstatgen, .flokisstatgen *, .flokisstatgen *::before, .flokisstatgen *::after {
  box-sizing: border-box;
}
.flokisstatgen {
  --flokisScreenborder: #600000;
  --flokisGrey: #696969;
  /* The var() fallback is load-bearing for export. This CSS ships in a style
     element INSIDE the card, so el.outerHTML carries it into the PNG's isolated
     SVG foreignObject and the standalone HTML file, where --font-pt-sans is not
     defined. Without the fallback, that reference is invalid at computed-value
     time and discards the WHOLE font-family (reverting it to serif), reflowing
     the export so it no longer matches the preview. The fallback keeps it valid.
     (Keep the less-than character out of this CSS: the PNG path parses it as
     SVG/XML, where a bare one inside the style element breaks parsing.) */
  font-family: var(--font-pt-sans, "PT Sans"), "PT Sans", Arial, Helvetica, sans-serif;
  color: #020202 !important;
  background-color: #f8f4f0;
  width: 173mm;
  padding: 0 7px 7px;
  clear: both;
  font-size: 0.8em;
  font-weight: 300;
  font-kerning: auto;
  line-height: 1.5;
  letter-spacing: 0.02em;
  border: 3px #bcbcbc double;
  border-radius: 6px;
  margin: 0 auto 4px;
}
.flokisstatgen-SingleColumn { min-width: 100px; width: 340px; }
.flokisstatgen-Content { position: relative; }
/* Two-column mode: multicol lives on an inner wrapper that excludes the header,
   so no column-span is ever needed (WebKit mis-fragments spanning elements,
   duplicating the header). Single-column mode uses no multicol at all. */
.flokisstatgen:not(.flokisstatgen-SingleColumn) .flokisstatgen-Columns {
  columns: 2;
  column-gap: 8mm;
}
.flokisstatgen-likeyword, .flokisstatgen-keyword, .flokisstatgen strong, .flokisstatgen b {
  font-weight: bold; letter-spacing: 0.02em;
}
.flokisstatgen-keyword { color: #000000; }
.flokisstatgen-keyword::after { content: "\0000a0"; }
.flokisstatgen-title {
  font-family: var(--font-pt-sans, "PT Sans"), "PT Sans", Arial, Helvetica, sans-serif;
  font-size: 1.7em; font-weight: bold; letter-spacing: 0; text-transform: uppercase;
  color: #922610; padding: 0; margin: 0; width: 100%;
  border-bottom: 1px var(--flokisScreenborder) solid;
}
.flokisstatgen-sizetypetagsalignment {
  font-style: italic; color: #8a7a6a; margin-top: 2px; margin-bottom: 3px; padding-bottom: 2px;
}
.flokisstatgen-core { color: #000000; }
.flokisstatgen-general, .flokisstatgen-general2, .flokisstatgen-general3 { break-inside: avoid; border: none; }
.flokisstatgen-general2 { width: 100%; display: flex; }
.flokisstatgen-general2 > * { flex: 1 1 50%; min-width: 0; }
.flokisstatgen-abilities {
  box-sizing: border-box; break-inside: avoid; display: flex; flex-direction: row;
  flex-wrap: nowrap; justify-content: space-between; gap: 12px; width: 100%;
  clear: both; border: none; font-size: 1.1em;
}
/* flex:1 1 0 + min-width:0 lets the two tables shrink to share the row; a bare
   flex:1 keeps min-width:auto, so the border-collapse tables stay at their
   content min-width and the pair + gap overflows the card's right edge. width:100%
   + table-layout:fixed gives fixed layout a definite basis so columns distribute
   within the shared width instead of forcing the table wider. */
.flokisstatgen-abilitiesblock {
  border-collapse: collapse; border-spacing: 0; margin: 2px 0;
  flex: 1 1 0; min-width: 0; width: 100%; table-layout: fixed; color: #000000;
}
.flokisstatgen-physicalabilities { background-color: #f0e8e0; }
.flokisstatgen-physicalmods { background-color: #e0ccc4; }
.flokisstatgen-mentalabilities { background-color: #d8d8d0; }
.flokisstatgen-mentalmods { background-color: #ccc4c8; }
.flokisstatgen-abilitiesblock th {
  font-size: 1em; font-weight: lighter; text-transform: lowercase; font-variant: small-caps;
  text-align: right; padding: 2px 5px; line-height: 1.3; color: var(--flokisGrey);
}
.flokisstatgen-abilitiesblock td { padding: 4px 5px; line-height: 1.4; color: #000000; }
.flokisstatgen-ability { text-align: center; }
.flokisstatgen-abilityname {
  font-weight: bold; text-transform: uppercase; font-size: 0.85em; letter-spacing: 0.05em;
  text-align: left; padding-left: 3px; width: 1.5em;
}
.flokisstatgen-abilityscore, .flokisstatgen-abilitymodifier, .flokisstatgen-abilitysave {
  text-align: right; padding-right: 3px; width: 1.5em;
}
.flokisstatgen-features { border: none; margin-bottom: 2px; break-inside: avoid; }
.flokisstatgen-feature { text-indent: -1em; padding-left: 1em; margin-top: 1px; margin-bottom: 2px; }
.flokisstatgen-skill { color: #000000; }
.flokisstatgen-cr { margin-right: 3px !important; }
.flokisstatgen-sectionheader {
  color: #500000; text-transform: capitalize; font-size: 1.4em; letter-spacing: 0.02em;
  break-inside: avoid; width: 100%; margin-top: 10px; margin-bottom: 1px;
  border-bottom: 1px var(--flokisScreenborder) solid;
}
.flokisstatgen-sectionheader + .flokisstatgen-line { margin-top: 2px; }
.flokisstatgen-line { margin-top: 5px; margin-bottom: 2px; }
.flokisstatgen-line + .flokisstatgen-text { text-indent: 1em; margin-top: 2px; margin-bottom: 2px; }
.flokisstatgen-attacktype, .flokisstatgen-hit, .flokisstatgen-italic { font-style: italic; }
.flokisstatgen-hit::before { content: " "; }
.flokisstatgen-attacktype::after, .flokisstatgen-hit::after { content: "\0000a0"; }
.flokisstatgen-namedstring .flokisstatgen-keyword,
.flokisstatgen-attack .flokisstatgen-keyword,
.flokisstatgen-reaction .flokisstatgen-keyword { font-style: italic; }
.flokisstatgen-legendarytext { font-style: italic; color: var(--flokisGrey); }
.flokisstatgen-monster-image {
  float: right; max-width: 45%; max-height: 400px; margin: 5px 0 10px 15px;
  border: none; shape-outside: margin-box;
}
.flokisstatgen hr { margin: 2px 0; border: none; border-bottom: 1px var(--flokisScreenborder) solid; }
</style><div class="flokisstatgen-Content"><div class="flokisstatgen-header"><div class="flokisstatgen-section flokisstatgen-general"><p class="flokisstatgen-title"><span>Beast of the Land</span></p><p class="flokisstatgen-sizetypetagsalignment"><span>Medium Beast, Neutral</span></p></div></div><div class="flokisstatgen-Columns"><div class="flokisstatgen-core"><div class="flokisstatgen-section flokisstatgen-general2"><p class="flokisstatgen-feature"><span class="flokisstatgen-keyword">AC</span><span>13 plus your Wisdom modifier</span></p></div><div class="flokisstatgen-section flokisstatgen-general3"><p class="flokisstatgen-feature"><span class="flokisstatgen-keyword">HP</span><span>5 plus five times your Ranger level (the beast has a number of Hit Dice [d8s] equal to your Ranger level)</span></p><p class="flokisstatgen-feature"><span class="flokisstatgen-keyword">Speed</span><span>40 ft., Climb 40 ft.</span></p></div><div class="flokisstatgen-section flokisstatgen-abilities"><table class="flokisstatgen-abilitiesblock"><thead><tr><th></th><th></th><th>mod</th><th>save</th></tr></thead><tbody><tr class="flokisstatgen-ability"><td class="flokisstatgen-abilityname flokisstatgen-physicalabilities">Str</td><td class="flokisstatgen-abilityscore flokisstatgen-physicalabilities">14</td><td class="flokisstatgen-abilitymodifier flokisstatgen-physicalmods">+2</td><td class="flokisstatgen-abilitysave flokisstatgen-physicalmods">+2</td></tr><tr class="flokisstatgen-ability"><td class="flokisstatgen-abilityname flokisstatgen-physicalabilities">Dex</td><td class="flokisstatgen-abilityscore flokisstatgen-physicalabilities">14</td><td class="flokisstatgen-abilitymodifier flokisstatgen-physicalmods">+2</td><td class="flokisstatgen-abilitysave flokisstatgen-physicalmods">+2</td></tr><tr class="flokisstatgen-ability"><td class="flokisstatgen-abilityname flokisstatgen-physicalabilities"><span style="white-space:nowrap;">Con</span></td><td class="flokisstatgen-abilityscore flokisstatgen-physicalabilities">15</td><td class="flokisstatgen-abilitymodifier flokisstatgen-physicalmods">+2</td><td class="flokisstatgen-abilitysave flokisstatgen-physicalmods">+2</td></tr></tbody></table><table class="flokisstatgen-abilitiesblock"><thead><tr><th></th><th></th><th>mod</th><th>save</th></tr></thead><tbody><tr class="flokisstatgen-ability"><td class="flokisstatgen-abilityname flokisstatgen-mentalabilities">Int</td><td class="flokisstatgen-abilityscore flokisstatgen-mentalabilities">8</td><td class="flokisstatgen-abilitymodifier flokisstatgen-mentalmods">-1</td><td class="flokisstatgen-abilitysave flokisstatgen-mentalmods">-1</td></tr><tr class="flokisstatgen-ability"><td class="flokisstatgen-abilityname flokisstatgen-mentalabilities">Wis</td><td class="flokisstatgen-abilityscore flokisstatgen-mentalabilities">14</td><td class="flokisstatgen-abilitymodifier flokisstatgen-mentalmods">+2</td><td class="flokisstatgen-abilitysave flokisstatgen-mentalmods">+2</td></tr><tr class="flokisstatgen-ability"><td class="flokisstatgen-abilityname flokisstatgen-mentalabilities"><span style="white-space:no-wrap;">Cha</span></td><td class="flokisstatgen-abilityscore flokisstatgen-mentalabilities">11</td><td class="flokisstatgen-abilitymodifier flokisstatgen-mentalmods">+0</td><td class="flokisstatgen-abilitysave flokisstatgen-mentalmods">+0</td></tr></tbody></table></div><div class="flokisstatgen-section flokisstatgen-features"><p class="flokisstatgen-feature"><span class="flokisstatgen-keyword">Senses</span><span><a href="darkvision">Darkvision</a> 60 ft.; Passive Perception 12</span></p><p class="flokisstatgen-feature"><span class="flokisstatgen-keyword">Languages</span><span>Understands the languages you know</span></p><p class="flokisstatgen-feature"><span class="flokisstatgen-keyword">CR</span><span>None (XP 0; PB equals your Proficiency Bonus)</span></p></div></div><div class="flokisstatgen-body"><div class="flokisstatgen-section"><div class="flokisstatgen-sectionheader">Traits</div><p class="flokisstatgen-line flokisstatgen-namedstring"><span class="flokisstatgen-keyword">Primal Bond.</span><span>Add your Proficiency Bonus to any ability check or saving throw the beast makes.</span></p></div><div class="flokisstatgen-section"><div class="flokisstatgen-sectionheader">Actions</div><p class="flokisstatgen-line flokisstatgen-attack"><span class="flokisstatgen-keyword">Beast’s Strike<!-- -->.</span><span><span class="flokisstatgen-attacktype">Melee Attack Roll:</span> Bonus equals your spell attack modifier, reach 5 ft. <span class="flokisstatgen-hit">Hit:</span> 1d8 + 2 plus your Wisdom modifier Bludgeoning, Piercing, or Slashing damage (your choice when you summon the beast). If the beast moved at least 20 feet straight toward the target before the hit, the target takes an extra 1d6 damage of the same type, and the target has the <a href="prone">Prone</a> condition if it is a Large or smaller creature.</span></p></div></div></div></div></div></body></html>

![[Images/Beast of the Sea.statblockwizard.png]]

![[Images/Beast of the Sky.statblockwizard.png]]

### Level 7: Exceptional Training

When you take a [[Bonus Action]] to command your Primal Companion beast to take an action, you can also command it to take the [[Dash]], [[Disengage]], [[Dodge]], or [[Help]] action using its Bonus Action.

In addition, whenever it hits with an attack roll and deals damage, it can deal your choice of Force damage or its normal damage type.

### Level 11: Bestial Fury

When you command your Primal Companion beast to take the Beast’s Strike action, the beast can use it twice.

In addition, the first time each turn it hits a creature under the effect of your _[[Hunter's Mark]]_ spell, the beast deals extra Force damage equal to the bonus damage of that spell.

### Level 15: Share Spells

When you cast a spell targeting yourself, you can also affect your Primal Companion beast with the spell if the beast is within 30 feet of you.
