---
title: "{{title}}"
subtitle: "*{{epithet}}*"
image: "{{image}}"
tags: [Deity, Pantheon]

# Core Identity
Domains: "{{domains}}"                 # e.g., War, Knowledge, Death
Alignment: "{{alignment}}"
Symbol: "{{symbol}}"
SacredAnimal: "{{animal}}"
SacredColors: "{{colors}}"
AssociatedElements: "{{elements}}"     # e.g., Fire, Light, Creation

# Worship
Worshipers: "{{worshipers}}"            # e.g., [[Felinnari]], warriors
Temples: "{{temples}}"                  # Architectural style, locations
ClergyName: "{{clergy}}"                # e.g., Priests, Hierophants
ClergyAlignment: "{{clergy_align}}"
Rites: "{{rites}}"                      # Brief description
HolyDays: "{{holy_days}}"               # Major festivals

# Relationships
Pantheon: "{{pantheon}}"                # Which pantheon they belong to
Parents: "{{parents}}"
Siblings: "{{siblings}}"
Consorts: "{{consorts}}"
Children: "{{children}}"
Allies: "{{allies}}"
Enemies: "{{enemies}}"

# Game Mechanics (if applicable)
FavoredWeapon: "{{weapon}}"
ClericDomains: "{{cleric_domains}}"     # For D&D-style games
Blessing: "{{blessing}}"                 # Example blessing

layout:
  - type: header
    text: "Identity"
    above: Domains
  - type: group
    keys: [Domains, Alignment, Symbol]
  - type: group
    keys: [SacredAnimal, SacredColors, AssociatedElements]

  - type: header
    text: "Worship"
    above: Worshipers
  - type: group
    keys: [Worshipers, Temples, ClergyName, ClergyAlignment]
  - type: group
    keys: [Rites, HolyDays]

  - type: header
    text: "Relationships"
    above: Pantheon
  - type: group
    keys: [Pantheon, Parents, Siblings, Consorts, Children]
  - type: group
    keys: [Allies, Enemies]

  - type: header
    text: "Game Mechanics"
    above: FavoredWeapon
  - type: group
    keys: [FavoredWeapon, ClericDomains, Blessing]
---
# Description
[General overview of the deity, their appearance, personality, and role.]

# Mythology
[Stories, creation myths, legendary deeds.]

# Dogma
[Teachings, commandments, what they expect from followers.]

# Worship
[Detailed practices, prayers, sacrifices, temple life.]

# Clergy
[Hierarchy, requirements, daily duties, special abilities.]

# Holy Sites
[Important temples, shrines, sacred geography.]

# Relationships
[Alliances, rivalries, family ties with other deities.]

# Interaction with Mortals
[How they manifest, omens, intervention.]

# In the Game
[Mechanical benefits for followers, quest hooks, symbols to encounter.]

# Notes