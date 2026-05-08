---
title: "{{title}}"
subtitle: "*{{season_type}}*"
image: "{{image}}"
tags: [Season, Calendar, Weather]

# Overview
SeasonType: "{{season_type}}"              # e.g., Spring, Summer, Autumn, Winter, Monsoon, Dry
Duration: "{{duration}}"                    # e.g., 3 months, 90 days, Lunar cycle
Position: "{{position}}"                     # e.g., First, Second, Third, Fourth
Region: "{{region}}"                         # Where this season applies (link to [[Region]] or [[World]])

# Weather
TypicalTemperature: "{{temperature}}"         # Range or average
Precipitation: "{{precipitation}}"             # Rain, snow, etc.
SkyConditions: "{{sky}}"                        # Sunny, cloudy, stormy
ExtremeWeather: "{{extreme}}"                   # Hurricanes, blizzards, heatwaves

# Light
DayLength: "{{day_length}}"                     # Hours of daylight
NightLength: "{{night_length}}"                  # Hours of darkness
SunPosition: "{{sun_position}}"                   # Low, high, etc.

# Cultural
AssociatedHolidays: "{{holidays}}"               # Festivals, religious observances
Traditions: "{{traditions}}"                      # Customs, activities
Symbolism: "{{symbolism}}"                         # What the season represents
Colors: "{{colors}}"                               # Seasonal color palette

# Ecological
FloraChanges: "{{flora}}"                          # Blooming, shedding, dormancy
FaunaChanges: "{{fauna}}"                          # Migration, hibernation, mating
AgriculturalActivities: "{{agriculture}}"          # Planting, harvesting

# Magical (if applicable)
MagicalFlux: "{{magic}}"                           # How magic changes
AssociatedElements: "{{elements}}"                  # Elemental affinities

layout:
  - type: header
    text: "Season Overview"
    above: SeasonType
  - type: group
    keys: [SeasonType, Duration, Position, Region]

  - type: header
    text: "Weather"
    above: TypicalTemperature
  - type: group
    keys: [TypicalTemperature, Precipitation, SkyConditions, ExtremeWeather]

  - type: header
    text: "Light"
    above: DayLength
  - type: group
    keys: [DayLength, NightLength, SunPosition]

  - type: header
    text: "Cultural"
    above: AssociatedHolidays
  - type: group
    keys: [AssociatedHolidays, Traditions, Symbolism, Colors]

  - type: header
    text: "Ecological"
    above: FloraChanges
  - type: group
    keys: [FloraChanges, FaunaChanges, AgriculturalActivities]

  - type: header
    text: "Magical"
    above: MagicalFlux
  - type: group
    keys: [MagicalFlux, AssociatedElements]
---
# Description
[Evocative description of the season: its mood, beauty, and sensory details.]

# Weather Patterns
[In-depth look at typical weather during this season, including variations and extremes.]

# Light & Darkness
[How daylight length affects daily life, activities, and psychology.]

# Cultural Significance
[Holidays, festivals, traditions, and the season's place in art and literature.]

# Flora & Fauna
[Detailed changes in plant and animal life during this season.]

# Agriculture & Economy
[Farming activities, harvests, hunting seasons, economic impacts.]

# Magical Associations
[If magic fluctuates with seasons, describe effects on spellcasting, alchemy, etc.]

# Survival & Adventuring
[Tips for travelers: what to wear, what dangers to expect.]

# In the Game
[Mechanical effects: bonuses/penalties to certain activities, seasonal encounters.]

# Notes