---
title: "{{title}}"
subtitle: "*{{species_name}}*"
image: "{{image}}"
tags: [Flora, Plant, Fungus]

# Taxonomy
CommonName: "{{common_name}}"
ScientificName: "{{scientific_name}}"
Family: "{{family}}"
Type: "{{type}}"                              # e.g., Tree, Shrub, Flower, Fungus, Moss
Habitat: "{{habitat}}"                         # Where it grows (links to [[Region]])

# Description
Size: "{{size}}"                               # Height, spread
Appearance: "{{appearance}}"                    # Leaves, bark, flowers, colors
DistinguishingFeatures: "{{features}}"          # Thorns, bioluminescence, scent
BloomTime: "{{bloom}}"                          # Season of flowering/fruiting

# Ecology
GrowthRate: "{{growth}}"                        # Slow, Moderate, Fast
Lifespan: "{{lifespan}}"
SoilPreferences: "{{soil}}"
SunRequirements: "{{sun}}"                       # Full sun, shade, etc.
WaterRequirements: "{{water}}"                   # Dry, moist, aquatic
AssociatedSpecies: "{{associated}}"               # Animals that depend on it

# Reproduction
ReproductionMethod: "{{reproduction}}"            # Seeds, spores, cuttings
Pollination: "{{pollination}}"                    # Wind, insects, animals
SeedDispersal: "{{dispersal}}"

# Uses
Edibility: "{{edibility}}"                        # Edible, poisonous, medicinal
MedicinalProperties: "{{medicinal}}"
MaterialUses: "{{materials}}"                      # Wood, fiber, dye
AlchemicalUses: "{{alchemical}}"                   # Potion ingredients
MagicalProperties: "{{magical}}"                    # If applicable

# Cultivation
Domesticability: "{{domestic}}"                    # Can be cultivated?
GrowingConditions: "{{conditions}}"
Harvesting: "{{harvest}}"                          # Season, method

# Hazards
Toxicity: "{{toxicity}}"                           # Poisonous parts, effects
Thorns: "{{thorns}}"
Allergens: "{{allergens}}"
InvasivePotential: "{{invasive}}"

# Cultural Significance
Symbolism: "{{symbolism}}"
Myths: "{{myths}}"
ReligiousUse: "{{religious}}"

# Game Mechanics (if applicable)
HarvestDC: "{{harvest_dc}}"
Yield: "{{yield}}"
Value: "{{value}}"
SpecialEffects: "{{effects}}"

layout:
  - type: header
    text: "Taxonomy"
    above: CommonName
  - type: group
    keys: [CommonName, ScientificName, Family, Type, Habitat]

  - type: header
    text: "Description"
    above: Size
  - type: group
    keys: [Size, Appearance, DistinguishingFeatures, BloomTime]

  - type: header
    text: "Ecology"
    above: GrowthRate
  - type: group
    keys: [GrowthRate, Lifespan, SoilPreferences, SunRequirements, WaterRequirements, AssociatedSpecies]

  - type: header
    text: "Reproduction"
    above: ReproductionMethod
  - type: group
    keys: [ReproductionMethod, Pollination, SeedDispersal]

  - type: header
    text: "Uses"
    above: Edibility
  - type: group
    keys: [Edibility, MedicinalProperties, MaterialUses, AlchemicalUses, MagicalProperties]

  - type: header
    text: "Cultivation"
    above: Domesticability
  - type: group
    keys: [Domesticability, GrowingConditions, Harvesting]

  - type: header
    text: "Hazards"
    above: Toxicity
  - type: group
    keys: [Toxicity, Thorns, Allergens, InvasivePotential]

  - type: header
    text: "Cultural Significance"
    above: Symbolism
  - type: group
    keys: [Symbolism, Myths, ReligiousUse]

  - type: header
    text: "Game Mechanics"
    above: HarvestDC
  - type: group
    keys: [HarvestDC, Yield, Value, SpecialEffects]
---
# Description
[Detailed botanical description, including growth habit, seasonal changes, and notable features.]

# Habitat & Distribution
[Where it grows naturally, geographic range, preferred environment.]

# Ecology
[Role in the ecosystem, interactions with animals and other plants.]

# Life Cycle
[Germination, growth, flowering, fruiting, death.]

# Uses
[Practical applications by sentient beings – food, medicine, materials, magic.]

# Cultivation
[How to grow it, challenges, optimal conditions, harvesting methods.]

# Toxicity & Hazards
[Dangers, poisoning symptoms, first aid.]

# Lore & Legends
[Stories, superstitions, magical beliefs.]

# Game Statistics
[If needed, detailed mechanics for harvesting, crafting, or alchemical use.]

# Adventure Hooks
[Plot ideas involving this plant – quest for rare herb, poisonous threat, etc.]

# Notes