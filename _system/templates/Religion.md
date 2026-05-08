---
title: "{{title}}"
subtitle: "*{{tradition}}*"
image: "{{image}}"
tags: [Religion, Institution]

# Overview
Tradition: "{{tradition}}"              # e.g., Monotheistic, Polytheistic, Animistic
DeitiesWorshiped: "{{deities}}"          # List of deities (if any)
Founder: "{{founder}}"                   # Historical or mythical founder
Founded: "{{founded}}"                    # Date or era
Headquarters: "{{hq}}"                    # Center of the religion

# Beliefs
CoreTenets: "{{tenets}}"                  # Key beliefs
SacredTexts: "{{texts}}"                  # Holy books
Afterlife: "{{afterlife}}"                 # What they believe happens after death
ViewsOnMagic: "{{magic_views}}"            # Acceptance, prohibition

# Structure
ClergyHierarchy: "{{hierarchy}}"
ClergyTitles: "{{titles}}"
InitiationRites: "{{initiation}}"
PlacesOfWorship: "{{places}}"

# Practices
Rituals: "{{rituals}}"
PrayerFrequency: "{{prayer}}"
DietaryLaws: "{{diet}}"
HolyDays: "{{holy_days}}"
Pilgrimages: "{{pilgrimages}}"

# Influence
Followers: "{{followers}}"                 # Approximate number or demographics
Regions: "{{regions}}"                      # Where it is practiced
PoliticalPower: "{{political_power}}"       # Influence over governments
RelationsWithOtherReligions: "{{relations}}"

layout:
  - type: header
    text: "Overview"
    above: Tradition
  - type: group
    keys: [Tradition, DeitiesWorshiped, Founder, Founded, Headquarters]

  - type: header
    text: "Beliefs"
    above: CoreTenets
  - type: group
    keys: [CoreTenets, SacredTexts, Afterlife, ViewsOnMagic]

  - type: header
    text: "Structure"
    above: ClergyHierarchy
  - type: group
    keys: [ClergyHierarchy, ClergyTitles, InitiationRites, PlacesOfWorship]

  - type: header
    text: "Practices"
    above: Rituals
  - type: group
    keys: [Rituals, PrayerFrequency, DietaryLaws, HolyDays, Pilgrimages]

  - type: header
    text: "Influence"
    above: Followers
  - type: group
    keys: [Followers, Regions, PoliticalPower, RelationsWithOtherReligions]
---
# Description
[What this religion is known for, its character, and its role in society.]

# History
[Origin, schisms, reformations, key historical moments.]

# Beliefs & Doctrine
[Detailed explanation of theology, cosmology, and moral teachings.]

# Sacred Texts
[Descriptions of holy books, what they contain.]

# Worship & Rituals
[How followers practice their faith day-to-day and on special occasions.]

# Clergy
[Roles, training, lifestyle of religious leaders.]

# Places of Worship
[Architecture, sacred sites, local shrines.]

# Festivals & Holy Days
[Annual celebrations, their meaning and customs.]

# Relations with Other Faiths
[Ecumenical dialogues, conflicts, persecution.]

# In the Game
[How this religion affects adventures: quests, NPCs, roleplaying opportunities.]

# Notes