---
title: "{{title}}"
subtitle: "*{{biome_type}}*"
image: "{{image}}"
tags: [Region, Geography, Biome]

# Overview
BiomeType: "{{biome_type}}"              # e.g., Forest, Desert, Tundra, Swamp
Size: "{{size}}"                          # e.g., 500 sq miles
Location: "{{location}}"                   # Where it's situated (continent, country)
Coordinates: "{{coordinates}}"             # Optional, for maps
InfluencedBy: "{{influenced}}"             # e.g., Ocean currents, mountains

# Climate
ClimateZone: "{{climate_zone}}"            # e.g., Tropical, Temperate, Polar
AverageTemperature: "{{temperature}}"      # e.g., 20°C, varies by season
Rainfall: "{{rainfall}}"                    # e.g., Heavy, Seasonal, Arid
Seasons: "{{seasons}}"                      # Description of seasonal changes

# Geography
Terrain: "{{terrain}}"                      # Detailed terrain features
Elevation: "{{elevation}}"                  # Average height above sea level
WaterFeatures: "{{water}}"                  # Rivers, lakes, oceans
SoilType: "{{soil}}"                        # e.g., Sandy, Loamy, Permafrost

# Ecology
Flora: "{{flora}}"                          # Dominant plant types, links to [[Flora]] notes
Fauna: "{{fauna}}"                          # Dominant animal types, links to [[Fauna]] notes
EndemicSpecies: "{{endemic}}"                # Species found only here
InvasiveSpecies: "{{invasive}}"              # Non-native species

# Natural Resources
Minerals: "{{minerals}}"
Timber: "{{timber}}"
Game: "{{game}}"
RareMaterials: "{{rare}}"

# Hazards
NaturalHazards: "{{hazards}}"                # e.g., Floods, Volcanoes, Quicksand
Diseases: "{{diseases}}"                      # Regional illnesses
DangerousCreatures: "{{creatures}}"           # Predators, monsters

# Human/NPC Interaction
Settlements: "{{settlements}}"                # Towns, camps within
Routes: "{{routes}}"                          # Trails, roads
ResourceExtraction: "{{extraction}}"           # Mining, logging, hunting
CulturalSignificance: "{{cultural}}"           # Sacred sites, folklore

layout:
  - type: header
    text: "Region Overview"
    above: BiomeType
  - type: group
    keys: [BiomeType, Size, Location, Coordinates, InfluencedBy]

  - type: header
    text: "Climate"
    above: ClimateZone
  - type: group
    keys: [ClimateZone, AverageTemperature, Rainfall, Seasons]

  - type: header
    text: "Geography"
    above: Terrain
  - type: group
    keys: [Terrain, Elevation, WaterFeatures, SoilType]

  - type: header
    text: "Ecology"
    above: Flora
  - type: group
    keys: [Flora, Fauna, EndemicSpecies, InvasiveSpecies]

  - type: header
    text: "Resources"
    above: Minerals
  - type: group
    keys: [Minerals, Timber, Game, RareMaterials]

  - type: header
    text: "Hazards"
    above: NaturalHazards
  - type: group
    keys: [NaturalHazards, Diseases, DangerousCreatures]

  - type: header
    text: "Human Interaction"
    above: Settlements
  - type: group
    keys: [Settlements, Routes, ResourceExtraction, CulturalSignificance]
---
# Description
[Evocative introduction to the region's appearance, atmosphere, and feel.]

# Geography
[Detailed description of landforms, water bodies, notable landmarks.]

# Climate & Weather
[In-depth seasonal patterns, typical weather, extreme events.]

# Flora
[Overview of plant life, including dominant species and their roles in the ecosystem.]

# Fauna
[Overview of animal life, including keystone species and their behaviors.]

# Ecosystem Dynamics
[How the food web works, predator-prey relationships, symbiotic interactions.]

# Natural Resources
[What can be harvested, where, and by whom.]

# Hazards & Survival
[What makes this region dangerous, how to prepare, local survival knowledge.]

# Inhabitation
[Permanent or seasonal settlements, nomadic groups, resource camps.]

# Lore & Legends
[Myths, spirits, or legendary creatures associated with the region.]

# Adventure Hooks
[Plot ideas tied to the region's features.]

# Notes