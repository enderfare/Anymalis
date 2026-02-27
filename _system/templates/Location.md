---
title: "{{title}}"
subtitle: "*{{epithet}}*"
image: 
  - ["{{image1}}", "{{caption1}}"]
  - ["{{image2}}", "{{caption2}}"]
tags: [Location, "{{type}}", Region]
Type: "{{type}}"
Population: "{{population}}"
Ruler: "{{ruler}}"
Government: "{{gov}}"
Exports: "{{exports}}"
Imports: "{{imports}}"
Crime: "{{crime}}"
Notable_Factions: [Faction1, Faction2]
Affiliated_Species: [Species1, Species2]

layout:
  - type: header
    text: "General"
    above: Type
  - type: group
    keys: [Type, Population, Ruler, Government]
  - type: separator
    above: Exports
  - type: group
    keys: [Exports, Imports, Crime]
  - type: header
    text: "Inhabitants"
    above: Notable_Factions
  - type: group
    keys: [Notable_Factions, Affiliated_Species]
---
# Description
[Overview, geography, atmosphere.]

# History
[Key events, founding, notable eras.]

# Districts / Regions
[Breakdown of important areas – can use subheadings or a gallery.]

# Points of Interest
- **[Name]:** [description]

# Notable Figures
- [[Name]] – [role]

# Factions & Politics
[Local powers, conflicts, alliances.]

# Economy
[Trade, currency, major industries.]

# Flora & Fauna
| Name | Type | Notes |
|------|------|-------|
| ...  |      |       |

# Adventure Hooks
[Potential plot seeds.]

# Gallery
<div class="gallery">
  <figure>![[image.jpg]]<figcaption>caption</figcaption></figure>
</div>