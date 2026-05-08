---
title: "{{title}}"
subtitle: "*{{ecosystem_type}}*"
image: "{{image}}"
tags: [Ecosystem, Ecology]

# Overview
EcosystemType: "{{ecosystem_type}}"          # e.g., Forest, Wetland, Marine, Urban
Biome: "{{biome}}"                            # Link to parent [[Biome]]
Location: "{{location}}"                       # Specific area (region, coordinates)
Size: "{{size}}"                               # Approximate area

# Abiotic Factors
Climate: "{{climate}}"                         # Local climate conditions
SoilType: "{{soil}}"                           # Soil characteristics
WaterSources: "{{water}}"                       # Rivers, lakes, groundwater
Topography: "{{topography}}"                     # Landscape features

# Biotic Components
Producers: "{{producers}}"                       # Plants, algae, phytoplankton
Consumers: "{{consumers}}"                       # Herbivores, carnivores, omnivores
Decomposers: "{{decomposers}}"                   # Fungi, bacteria
KeystoneSpecies: "{{keystone}}"                   # Species with disproportionate impact

# Ecological Relationships
FoodWeb: "{{food_web}}"                          # Description of energy flow
SymbioticRelationships: "{{symbiosis}}"           # Mutualism, commensalism, parasitism
Competition: "{{competition}}"                     # Interspecific and intraspecific
PredatorPrey: "{{predator_prey}}"                  # Key dynamics

# Ecosystem Health
Status: "{{status}}"                              # Pristine, Threatened, Degraded
Threats: "{{threats}}"                             # Pollution, invasive species, climate change
ConservationEfforts: "{{conservation}}"             # Protection measures

# Services
EcosystemServices: "{{services}}"                  # Benefits to humans (clean water, pollination)
Resources: "{{resources}}"                          # Harvestable materials

layout:
  - type: header
    text: "Ecosystem Overview"
    above: EcosystemType
  - type: group
    keys: [EcosystemType, Biome, Location, Size]

  - type: header
    text: "Abiotic Factors"
    above: Climate
  - type: group
    keys: [Climate, SoilType, WaterSources, Topography]

  - type: header
    text: "Biotic Components"
    above: Producers
  - type: group
    keys: [Producers, Consumers, Decomposers, KeystoneSpecies]

  - type: header
    text: "Ecological Relationships"
    above: FoodWeb
  - type: group
    keys: [FoodWeb, SymbioticRelationships, Competition, PredatorPrey]

  - type: header
    text: "Ecosystem Health"
    above: Status
  - type: group
    keys: [Status, Threats, ConservationEfforts]

  - type: header
    text: "Services"
    above: EcosystemServices
  - type: group
    keys: [EcosystemServices, Resources]
---
# Description
[Detailed description of this specific ecosystem, its character, and unique features.]

# Habitat Structure
[Physical structure: layers (canopy, understory), zones (littoral, profundal), etc.]

# Species Interactions
[In-depth look at key relationships: pollination, seed dispersal, predation.]

# Energy Flow & Nutrient Cycling
[How energy moves through trophic levels, carbon/nitrogen cycles.]

# Seasonal Dynamics
[How the ecosystem changes through the year.]

# Disturbance & Succession
[Natural disturbances and how the ecosystem recovers.]

# Human Impact
[Specific ways humans interact with or affect this ecosystem.]

# Monitoring & Research
[Any studies or observations.]

# Adventure Hooks
[Plot ideas based on ecosystem dynamics (e.g., invasive species, ecological disaster).]

# Notes