---
title: "{{title}}"
subtitle: "*{{species_name}}*"
image: "{{image}}"
tags: [Fauna, Creature, Animal]

# Taxonomy
CommonName: "{{common_name}}"
ScientificName: "{{scientific_name}}"       # Optional, for verisimilitude
Family: "{{family}}"                         # e.g., Canidae, Draconidae
Habitat: "{{habitat}}"                        # Where it lives (links to [[Region]])

# Description
Size: "{{size}}"                              # e.g., Small, Large, Dimensions
Weight: "{{weight}}"
Appearance: "{{appearance}}"                   # Brief summary, fur/scales, colors
DistinguishingFeatures: "{{features}}"         # Horns, tusks, bioluminescence

# Behavior
Diet: "{{diet}}"                               # e.g., Herbivore, Carnivore, Omnivore
ActivityCycle: "{{activity}}"                   # Diurnal, Nocturnal, Crepuscular
SocialStructure: "{{social}}"                   # Solitary, Packs, Herds
Temperament: "{{temperament}}"                  # Docile, Aggressive, Skittish
Intelligence: "{{intelligence}}"                 # Animalistic, Highly intelligent

# Ecology
RoleInEcosystem: "{{role}}"                     # e.g., Apex predator, Pollinator
Predators: "{{predators}}"                       # Natural enemies
Prey: "{{prey}}"                                 # What it eats
Symbionts: "{{symbionts}}"                       # Mutualistic relationships

# Reproduction
ReproductionMethod: "{{reproduction}}"           # e.g., Live birth, Eggs
Gestation: "{{gestation}}"
Offspring: "{{offspring}}"                       # Number per birth
Lifespan: "{{lifespan}}"

# Interaction with Sentient Beings
Domesticability: "{{domestic}}"                  # Tameable, Trainable
Uses: "{{uses}}"                                  # Food, fur, mounts, pets
DangerLevel: "{{danger}}"                         # Low, Medium, High
CulturalSignificance: "{{cultural}}"               # Sacred, hunted, feared

# Game Mechanics (if applicable)
CombatStats: "{{stats}}"                           # Brief or link to [[Monster]] statblock
SpecialAbilities: "{{abilities}}"
Loot: "{{loot}}"

layout:
  - type: header
    text: "Taxonomy"
    above: CommonName
  - type: group
    keys: [CommonName, ScientificName, Family, Habitat]

  - type: header
    text: "Description"
    above: Size
  - type: group
    keys: [Size, Weight, Appearance, DistinguishingFeatures]

  - type: header
    text: "Behavior"
    above: Diet
  - type: group
    keys: [Diet, ActivityCycle, SocialStructure, Temperament, Intelligence]

  - type: header
    text: "Ecology"
    above: RoleInEcosystem
  - type: group
    keys: [RoleInEcosystem, Predators, Prey, Symbionts]

  - type: header
    text: "Reproduction"
    above: ReproductionMethod
  - type: group
    keys: [ReproductionMethod, Gestation, Offspring, Lifespan]

  - type: header
    text: "Interaction"
    above: Domesticability
  - type: group
    keys: [Domesticability, Uses, DangerLevel, CulturalSignificance]

  - type: header
    text: "Game Mechanics"
    above: CombatStats
  - type: group
    keys: [CombatStats, SpecialAbilities, Loot]
---
# Description
[Full description of the creature, including its appearance, sounds, and typical encounters.]

# Habitat & Range
[Where it lives, territorial range, migration patterns.]

# Behavior & Ecology
[Daily activities, hunting/grazing patterns, social interactions, role in food web.]

# Life Cycle
[Birth, growth, mating, lifespan.]

# Uses & Interactions
[How sentient beings use or interact with this creature – hunting, domestication, cultural roles.]

# Lore & Legends
[Myths, stories, or superstitions about the creature.]

# Game Stats
[If needed, embed or link to a full statblock. For combat-ready creatures, consider using the [[Monster]] template.]

# Adventure Hooks
[Plot ideas involving this creature.]

# Notes