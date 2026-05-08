---
title: "{{title}}"
subtitle: "*The Seasons of {{region}}*"
image: "{{image}}"
tags: [Seasons, Calendar, Worldbuilding]

# Overview
Region: "{{region}}"                          # Where this system applies (link to [[Region]] or [[World]])
NumberOfSeasons: "{{count}}"                    # e.g., 4, 6, 13
CycleLength: "{{cycle_length}}"                  # e.g., 365 days, 360 days
ReferenceCalendar: "{{calendar}}"                 # Link to calendar system, if any

# Season List
Seasons:
  - "{{season1}}"  # Links to individual [[Season]] notes
  - "{{season2}}"
  - "{{season3}}"
  - "{{season4}}"

# Transitions
Equinoxes: "{{equinoxes}}"                        # Dates or descriptions
Solstices: "{{solstices}}"
CrossQuarterDays: "{{cross_quarter}}"              # Midpoints between solstices/equinoxes

# Cultural Calendar
NewYear: "{{new_year}}"                            # When the year begins
MajorFestivals: "{{festivals}}"                    # Key celebrations
AgriculturalCalendar: "{{agriculture}}"             # Planting, harvesting cycles

# Environmental
ClimatePatterns: "{{climate}}"                      # Overall climate description
EcologicalCycles: "{{ecology}}"                     # Migration, hibernation, blooming

# Magical (if applicable)
MagicalYear: "{{magic}}"                            # How magic flows through the year
ElementalCorrespondences: "{{elements}}"             # Which element rules which season

layout:
  - type: header
    text: "Seasons Overview"
    above: Region
  - type: group
    keys: [Region, NumberOfSeasons, CycleLength, ReferenceCalendar]

  - type: header
    text: "The Seasons"
    above: Seasons
  - type: group
    keys: [Seasons]

  - type: header
    text: "Transitions"
    above: Equinoxes
  - type: group
    keys: [Equinoxes, Solstices, CrossQuarterDays]

  - type: header
    text: "Cultural Calendar"
    above: NewYear
  - type: group
    keys: [NewYear, MajorFestivals, AgriculturalCalendar]

  - type: header
    text: "Environmental"
    above: ClimatePatterns
  - type: group
    keys: [ClimatePatterns, EcologicalCycles]

  - type: header
    text: "Magical"
    above: MagicalYear
  - type: group
    keys: [MagicalYear, ElementalCorrespondences]
---
# Description
[Introduction to the seasonal cycle of this region—its rhythm, character, and importance.]

# The Cycle
[Overview of how the seasons progress, their duration, and notable transitions.]

## [Season Name]
[Brief description of each season, with links to full Season notes.]

# Transitions
[Detailed explanation of equinoxes, solstices, and other significant turning points.]

# Cultural Significance
[How the seasonal cycle shapes festivals, traditions, and daily life.]

# Agricultural & Economic Impact
[Farming cycles, trade fluctuations, seasonal industries.]

# Ecological Rhythms
[Patterns of life: migration, breeding, blooming, dormancy.]

# Magical Flux
[If applicable, how magical energy waxes and wanes with the seasons.]

# In the Game
[How the seasonal system affects gameplay: travel times, resource availability, encounter tables.]

# Notes