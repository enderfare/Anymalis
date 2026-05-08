---
title: "{{title}}"
subtitle: "*{{associated_species}}*"
image: "{{image}}"
tags: [Culture, Society]

# Overview
AssociatedSpecies: "{{species}}"       # Primary species practicing this culture
Region: "{{region}}"                    # Geographical area
Era: "{{era}}"                          # Historical period, if applicable
InfluencedBy: "{{influenced}}"          # Other cultures that shaped it
Influenced: "{{influenced_cultures}}"   # Cultures it shaped

# Social Structure
Government: "{{government}}"             # Type of governance
SocialClasses: "{{classes}}"             # Hierarchy description
FamilyStructure: "{{family}}"            # Nuclear, extended, clan-based
GenderRoles: "{{gender_roles}}"          # Equality, patriarchy, matriarchy
ComingOfAge: "{{coming_of_age}}"         # Rites of passage

# Values & Beliefs
CoreValues: "{{values}}"                  # What they prize most
Taboos: "{{taboos}}"                      # Forbidden actions
Religion: "{{religion}}"                  # Dominant faiths
Philosophy: "{{philosophy}}"              # Worldview, proverbs

# Daily Life
Diet: "{{diet}}"                          # Typical foods
Clothing: "{{clothing}}"                  # Styles, materials
Housing: "{{housing}}"                    # Architecture
Occupations: "{{occupations}}"            # Common jobs
Leisure: "{{leisure}}"                    # Entertainment, sports

# Arts & Knowledge
ArtForms: "{{art}}"                       # Music, visual arts, dance
Literature: "{{literature}}"               # Oral tradition, writing
Education: "{{education}}"                 # How knowledge is passed
MagicAttitude: "{{magic_attitude}}"        # Acceptance, fear, integration

# Relations
Allies: "{{allies}}"
Enemies: "{{enemies}}"
TradePartners: "{{trade}}"
PerceptionByOthers: "{{perception}}"      # How outsiders see them

layout:
  - type: header
    text: "Culture Overview"
    above: AssociatedSpecies
  - type: group
    keys: [AssociatedSpecies, Region, Era, InfluencedBy, Influenced]

  - type: header
    text: "Social Structure"
    above: Government
  - type: group
    keys: [Government, SocialClasses, FamilyStructure, GenderRoles, ComingOfAge]

  - type: header
    text: "Values & Beliefs"
    above: CoreValues
  - type: group
    keys: [CoreValues, Taboos, Religion, Philosophy]

  - type: header
    text: "Daily Life"
    above: Diet
  - type: group
    keys: [Diet, Clothing, Housing, Occupations, Leisure]

  - type: header
    text: "Arts & Knowledge"
    above: ArtForms
  - type: group
    keys: [ArtForms, Literature, Education, MagicAttitude]

  - type: header
    text: "Relations"
    above: Allies
  - type: group
    keys: [Allies, Enemies, TradePartners, PerceptionByOthers]
---
# Description
[General introduction to the culture, its essence, and notable characteristics.]

# History & Origins
[How this culture came to be, migrations, historical influences.]

# Social Organization
[Detailed explanation of hierarchy, family, leadership.]

# Beliefs & Customs
[Rituals, festivals, superstitions, ethical code.]

# Arts & Expression
[Music, visual arts, storytelling, architecture.]

# Language & Communication
[Unique dialects, body language, etiquette.]

# Technology & Craftsmanship
[What they excel at making, tools, innovations.]

# Magic & the Supernatural
[Their relationship with magic, magical traditions, famous practitioners.]

# Relations with Other Cultures
[Diplomacy, conflicts, trade, cultural exchange.]

# Notable Figures
[Legendary heroes, rulers, artists.]

# Adventure Hooks
[Story ideas rooted in this culture.]

# Notes