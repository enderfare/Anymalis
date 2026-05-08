---
title: "{{title}}"
subtitle: "*{{climate_type}}*"
image: "{{image}}"
tags: [Climate, Zone, Geography]

# Overview
ClimateType: "{{climate_type}}"                # e.g., Tropical, Arid, Temperate, Continental, Polar
KöppenClassification: "{{koppen}}"              # If using real-world system (e.g., Af, BWh, Dfb)
Distribution: "{{distribution}}"                # Latitudes, typical locations

# Temperature
AverageAnnualTemperature: "{{avg_temp}}"
TemperatureRange: "{{temp_range}}"               # Seasonal variation
ExtremeTemperatures: "{{extreme}}"                # Record highs/lows

# Precipitation
AnnualPrecipitation: "{{precip}}"
RainySeason: "{{rainy_season}}"                  # Months or description
DrySeason: "{{dry_season}}"
Snowfall: "{{snow}}"                              # If applicable

# Atmospheric Patterns
PressureSystems: "{{pressure}}"                   # High/low pressure zones
Winds: "{{winds}}"                                 # Prevailing winds, monsoons
Humidity: "{{humidity}}"                           # Average or range

# Seasons
SeasonalPatterns: "{{seasons}}"                    # Description of each season
GrowingSeason: "{{growing}}"                        # Length of plant growing period

# Associated Biomes
TypicalBiomes: "{{biomes}}"                         # Biomes found in this climate zone

# Climate Change
Trends: "{{trends}}"                                # Changing patterns
Vulnerability: "{{vulnerability}}"                  # To droughts, floods, etc.

layout:
  - type: header
    text: "Climate Zone Overview"
    above: ClimateType
  - type: group
    keys: [ClimateType, KöppenClassification, Distribution]

  - type: header
    text: "Temperature"
    above: AverageAnnualTemperature
  - type: group
    keys: [AverageAnnualTemperature, TemperatureRange, ExtremeTemperatures]

  - type: header
    text: "Precipitation"
    above: AnnualPrecipitation
  - type: group
    keys: [AnnualPrecipitation, RainySeason, DrySeason, Snowfall]

  - type: header
    text: "Atmospheric Patterns"
    above: PressureSystems
  - type: group
    keys: [PressureSystems, Winds, Humidity]

  - type: header
    text: "Seasons"
    above: SeasonalPatterns
  - type: group
    keys: [SeasonalPatterns, GrowingSeason]

  - type: header
    text: "Associated Biomes"
    above: TypicalBiomes
  - type: group
    keys: [TypicalBiomes]

  - type: header
    text: "Climate Change"
    above: Trends
  - type: group
    keys: [Trends, Vulnerability]
---
# Description
[General description of this climate zone, its character, and global distribution.]

# Climate Characteristics
[Detailed breakdown of temperature, precipitation, and atmospheric dynamics.]

# Seasonal Cycle
[In-depth look at how seasons progress, with typical weather patterns.]

# Variability
[Interannual variability, extreme events (El Niño, droughts, etc.).]

# Impact on Life
[How plants, animals, and civilizations adapt to this climate.]

# Regions
[Examples of specific regions with this climate (can link to [[Region]] notes).]

# Climate History
[Past changes, ice ages, etc.]

# In the Game
[How this climate affects travel, survival, agriculture, and adventure.]

# Notes