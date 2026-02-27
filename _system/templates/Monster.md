---
title: "{{title}}"
subtitle: "*{{type}}, {{alignment}}*"
image: "{{image}}"
tags: [Monster, Creature]
Size: "{{size}}"
Type: "{{type}}"
Alignment: "{{alignment}}"
AC: "{{ac}}"
HP: "{{hp}}"
Speed: "{{speed}}"
STR: "{{str}} (+{{str_mod}})"
DEX: "{{dex}} (+{{dex_mod}})"
CON: "{{con}} (+{{con_mod}})"
INT: "{{int}} (+{{int_mod}})"
WIS: "{{wis}} (+{{wis_mod}})"
CHA: "{{cha}} (+{{cha_mod}})"
Saves: "{{saves}}"
Skills: "{{skills}}"
DamageResist: "{{resist}}"
DamageImmune: "{{immune}}"
ConditionImmune: "{{cond_immune}}"
Senses: "{{senses}}"
Languages: "{{languages}}"
Challenge: "{{cr}}"
Traits: 
  - "{{trait1}}"
  - "{{trait2}}"
Actions:
  - "{{action1}}"
  - "{{action2}}"
LegendaryActions: "{{legendary}}"

layout:
  - type: header
    text: "Defense"
    above: AC
  - type: group
    keys: [AC, HP, Speed]
  - type: header
    text: "Ability Scores"
    above: STR
  - type: group
    keys: [STR, DEX, CON]
  - type: group
    keys: [INT, WIS, CHA]
  - type: separator
    above: Saves
  - type: group
    keys: [Saves, Skills, DamageResist, DamageImmune, ConditionImmune]
  - type: group
    keys: [Senses, Languages, Challenge]
---
## Traits
**{{trait_name}}.** {{trait_description}}

## Actions
**{{action_name}}.** {{action_description}}

## Legendary Actions
{{legendary_description}}

## Description
[Lore, behavior, ecology.]

## Lair
[If applicable, lair actions and regional effects.]

## Treasure
[Typical hoard.]