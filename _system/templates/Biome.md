---
title: "{{title}}"
subtitle: "*{{classification}}*"
image: "{{image}}"
tags: [Biome, Ecology, Geography]

# Overview
Classification: "{{classification}}"        # e.g., Terrestrial, Aquatic, Artificial
Type: "{{type}}"                            # e.g., Tundra, Taiga, Rainforest, Desert, Grassland
ClimateZone: "{{climate_zone}}"              # Link to [[Climate Zone]]
Distribution: "{{distribution}}"              # Where found globally (real-world or fictional)

# Characteristics
AverageTemperature: "{{temperature}}"         # Range or average
Precipitation: "{{precipitation}}"             # Annual rainfall/ snowfall
Seasons: "{{seasons}}"                         # Description of seasonal patterns
SoilType: "{{soil}}"                           # Typical soil characteristics

# Flora & Fauna
DominantFlora: "{{flora}}"                     # Plant types, growth forms
DominantFauna: "{{fauna}}"                      # Animal types, adaptations
Biodiversity: "{{biodiversity}}"                # High, Moderate, Low
EndemicSpecies: "{{endemic}}"                   # Unique to this biome

# Ecological Dynamics
PrimaryProductivity: "{{productivity}}"         # Rate of biomass production
NutrientCycling: "{{nutrients}}"                 # How nutrients move
SuccessionPatterns: "{{succession}}"             # Ecological succession stages
DisturbanceRegimes: "{{disturbance}}"            # Fire, flood, storms

# Human/NPC Interaction
HumanInfluence: "{{human_influence}}"            # Agriculture, urbanization, conservation
Threats: "{{threats}}"                           # Deforestation, climate change
CulturalSignificance: "{{cultural}}"              # Myths, sacred sites

# Regions
ExampleRegions: "{{regions}}"                    # Links to specific [[Region]] notes

layout:
  - type: header
    text: "Biome Overview"
    above: Classification
  - type: group
    keys: [Classification, Type, ClimateZone, Distribution]

  - type: header
    text: "Characteristics"
    above: AverageTemperature
  - type: group
    keys: [AverageTemperature, Precipitation, Seasons, SoilType]

  - type: header
    text: "Flora & Fauna"
    above: DominantFlora
  - type: group
    keys: [DominantFlora, DominantFauna, Biodiversity, EndemicSpecies]

  - type: header
    text: "Ecological Dynamics"
    above: PrimaryProductivity
  - type: group
    keys: [PrimaryProductivity, NutrientCycling, SuccessionPatterns, DisturbanceRegimes]

  - type: header
    text: "Human Interaction"
    above: HumanInfluence
  - type: group
    keys: [HumanInfluence, Threats, CulturalSignificance]

  - type: header
    text: "Regions"
    above: ExampleRegions
  - type: group
    keys: [ExampleRegions]
---
# Description
[General description of the biome, its defining features, and overall character.]

# Climate & Environment
[Detailed explanation of climatic conditions, geography, and physical environment.]

# Flora
[Overview of plant life adapted to this biome, with examples and adaptations.]

# Fauna
[Overview of animal life, including key adaptations and ecological roles.]

# Ecological Processes
[How energy flows, nutrient cycles, food webs, and succession work here.]

# Subtypes
[Variations within the biome (e.g., different types of forests within the Temperate Forest biome).]

# Distribution
[Where this biome appears in the world, real or fictional.]

# Human Impact
[How sentient beings affect and are affected by this biome.]

# Adventure Hooks
[Plot ideas tied to the biome's characteristics.]

# Notes