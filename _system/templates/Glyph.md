---
title: "{{title}}"
subtitle: "*{{element}} – {{variant}}*"
image: "{{image}}"
tags: [Glyph, Template]
Element: "{{element}}"
Variant: "{{variant}}"
Outlines: "{{outlines}}"
ANICost: "{{cost}}"
CastingTime: "{{time}}"
Range: "{{range}}"
Duration: "{{duration}}"
SavingThrow: "{{save}}"
Components: "{{components}}"

layout:
  - type: header
    text: "Casting"
    above: Element
  - type: group
    keys: [Element, Variant, Outlines]
  - type: separator
    above: ANICost
  - type: group
    keys: [ANICost, CastingTime, Range, Duration]
  - type: group
    keys: [SavingThrow, Components]
---
# Description
[Flavor text, visual appearance when cast.]

# Effect
- **Base Effect:** [description]
- **At Higher ANI:** [scaling]

# Outline Interactions
- **[Outline]:** [modification]
- **[Outline]:** [modification]

# Visuals
[Detailed sensory description.]

# Notes
[Any additional mechanics, lore.]