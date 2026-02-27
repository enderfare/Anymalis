---
title: "{{title}}"
subtitle: "*{{ epithet }}*"
image: "{{image}}"
tags: [Character, "{{species}}", "{{archetype}}", Player/NPC]
Player: "{{player}}"
Species: "{{species}}"
Archetype: "{{archetype}}"
Age: "{{age}}"
Alignment: "{{alignment}}"
Patron Deity: "{{deity}}"
Homeland: "{{homeland}}"
Affinity Element: "{{element}}"
Affinity Variant: "{{variant}}"

# RPG Stats
str: "{{str}} (+{{str_mod}})"
dex: "{{dex}} (+{{dex_mod}})"
con: "{{con}} (+{{con_mod}})"
int: "{{int}} (+{{int_mod}})"
wis: "{{wis}} (+{{wis_mod}})"
cha: "{{cha}} (+{{cha_mod}})"
hp: "{{hp}}"
ac: "{{ac}}"
initiative: "{{init}}"
speed: "{{speed}}"
Prof_Bonus: "{{prof}}"
Passive_Perception: "{{passive_per}}"
Passive_Insight: "{{passive_ins}}"
Sanity: "{{current_san}}/{{max_san}}"
Energy: "{{current_enr}}/{{max_enr}}"
Animent: "{{current_ani}}/{{max_ani}}"
Glyphic_Ink: "{{ink}}"
ATS: "{{ats}}"
HTS: "{{hts}}"
Q: "{{q_percent}}%"

# Proficiencies (arrays)
Skills: [Skill1, Skill2, Skill3]
Skills_2: [Skill4, Skill5, Skill6]
Tools: [Tool1, Tool2]
Languages: [Lang1, Lang2]

layout:
  - type: header
    text: "Ability Scores"
    above: str
  - type: group
    keys: [str, dex, con]
  - type: group
    keys: [int, wis, cha]
  - type: separator
    above: hp
  - type: group
    keys: [hp, ac, initiative, speed]
  - type: header
    text: "Proficiencies"
    above: Skills
  - type: group
    keys: [Skills, Skills_2]
  - type: group
    keys: [Tools, Languages]
---
# Description
[Physical appearance, distinguishing marks, typical attire.]

# Personality
[Traits, ideals, bonds, flaws – can be formatted as a list or table.]

# Backstory
[History, key events, reasons for adventuring.]

# Attributes & Statistics
[Detailed breakdown of attribute scores, special stats, and derived values – can use tables.]

# Proficiencies
- **Saving Throws:** [list]
- **Skills:** Trained in [list], Expert in [list], Master in [list]
- **Tools:** [list]
- **Languages:** [list]

# Traits & Features
- **Racial Traits:** [from species]
- **Archetype Features:** [from archetype]
- **Animal/Hybrid Traits:** [if applicable]

# Elemental Affinity
- **Birthmark:** [description]
- **Affinity Effects:** [passive and active benefits]
- **Glyphs Known:** (list or table)

# Equipment
| Item | Weight | Value |
|------|--------|-------|
| ...  |        |       |

# Advancement Notes
[Training, glyph mastery, transformative events.]

# Notes
[Any additional info, GM secrets (use spoiler tags).]