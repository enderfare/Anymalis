---
title: "{{title}}"
subtitle: "*{{type}} – {{rarity}}*"
image: "{{image}}"
tags: [Item, Template]
Type: "{{type}}"
Rarity: "{{rarity}}"
Weight: "{{weight}} lbs"
Cost: "{{cost}}"
Attunement: "{{attunement}}"
Material: "{{material}}"
Properties: [Prop1, Prop2]
Charges: "{{charges}}"
Recharge: "{{recharge}}"

layout:
  - type: header
    text: "Details"
    above: Type
  - type: group
    keys: [Type, Rarity, Weight, Cost]
  - type: separator
    above: Attunement
  - type: group
    keys: [Attunement, Material]
  - type: group
    keys: [Properties]
  - type: header
    text: "Charges"
    above: Charges
  - type: group
    keys: [Charges, Recharge]
---
# Description
[Appearance, lore, notable history.]

# Properties
- **Weapon:** Damage [ ], Properties [ ]
- **Armor:** AC Bonus [ ], Max DEX [ ], Stealth [ ]
- **Focus:** Bonus [ ]
- **Consumable:** Effect [ ]

# Special Effects
[Magical properties, curses, etc.]

# Crafting Requirements
- **Materials:** [list]
- **Skills:** [required]
- **Time:** [duration]
- **Cost:** [resources]