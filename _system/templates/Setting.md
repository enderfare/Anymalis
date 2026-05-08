---
title: "{{title}}"
subtitle: "*{{region_type}}*"
image: "{{image}}"
tags: [Setting, Region]

# Overview
RegionType: "{{region_type}}"          # e.g., Kingdom, Continent, City-State
World: "{{world}}"                      # Link to parent world
Status: "{{status}}"                    # e.g., Active, WIP, Archived
Population: "{{population}}"             # Approximate number
Capital: "{{capital}}"

# Geography
Climate: "{{climate}}"
Terrain: "{{terrain}}"                   # e.g., Forests, Mountains, Plains
NotableLandmarks: "{{landmarks}}"
NaturalResources: "{{resources}}"

# Politics
Government: "{{government}}"
Ruler: "{{ruler}}"
MajorFactions: "{{factions}}"
PowerStruggles: "{{power_struggles}}"

# Demographics
Species: "{{species}}"
Languages: "{{languages}}"
Religion: "{{religion}}"
Culture: "{{culture}}"                   # Dominant cultural group

# Economy
Currency: "{{currency}}"
Exports: "{{exports}}"
Imports: "{{imports}}"
TradeRoutes: "{{trade_routes}}"

layout:
  - type: header
    text: "Setting Overview"
    above: RegionType
  - type: group
    keys: [RegionType, World, Status, Population, Capital]

  - type: header
    text: "Geography"
    above: Climate
  - type: group
    keys: [Climate, Terrain, NotableLandmarks, NaturalResources]

  - type: header
    text: "Politics"
    above: Government
  - type: group
    keys: [Government, Ruler, MajorFactions, PowerStruggles]

  - type: header
    text: "Demographics"
    above: Species
  - type: group
    keys: [Species, Languages, Religion, Culture]

  - type: header
    text: "Economy"
    above: Currency
  - type: group
    keys: [Currency, Exports, Imports, TradeRoutes]
---
# Description
[Evocative introduction to the setting, its mood, and its place in the world.]

# History
[Key events that shaped this region.]

# Geography
[Detailed description of terrain, climate, and important locations.]

# Settlements
[List and describe major cities, towns, and points of interest.]

# Politics & Factions
[In-depth look at the ruling powers, noble houses, guilds, and their conflicts.]

# People & Culture
[Daily life, customs, arts, cuisine, and social norms.]

# Economy & Trade
[Resources, industries, trade partners, and economic challenges.]

# Religion & Beliefs
[Local deities, religious practices, and superstitions.]

# Adventure Hooks
[Plot seeds specific to this region.]

# Notes