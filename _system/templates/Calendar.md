---
title: "{{title}}"
subtitle: "*{{type}}*"
image: "{{image}}"
tags: [Calendar, Holiday, Event]

# Overview
Type: "{{type}}"                       # e.g., Major Holiday, Seasonal Festival, Religious Observance
Culture: "{{culture}}"                  # Which culture celebrates it
Date: "{{date}}"                        # Day/Month/Year or relative position
Frequency: "{{frequency}}"              # e.g., Annual, Monthly, Once per Era
Duration: "{{duration}}"                # e.g., One day, Week-long

# Significance
Deity: "{{deity}}"                      # If religious
HistoricalEvent: "{{event}}"             # If commemorative
MythologicalBasis: "{{myth}}"            # Origin story
Purpose: "{{purpose}}"                   # e.g., Harvest, Remembrance, Renewal

# Observances
Traditions: "{{traditions}}"             # What people do
Food: "{{food}}"                         # Special dishes
Gifts: "{{gifts}}"                       # Exchanges
Clothing: "{{clothing}}"                 # Special attire
禁忌: "{{taboos}}"                       # Things to avoid during this time

# Mechanical Effects
GameEffects: "{{effects}}"               # e.g., Blessings, curses, temporary bonuses
RelatedQuests: "{{quests}}"              # Adventuring opportunities

layout:
  - type: header
    text: "Holiday Info"
    above: Type
  - type: group
    keys: [Type, Culture, Date, Frequency, Duration]

  - type: header
    text: "Significance"
    above: Deity
  - type: group
    keys: [Deity, HistoricalEvent, MythologicalBasis, Purpose]

  - type: header
    text: "Observances"
    above: Traditions
  - type: group
    keys: [Traditions, Food, Gifts, Clothing, Taboos]

  - type: header
    text: "Game Effects"
    above: GameEffects
  - type: group
    keys: [GameEffects, RelatedQuests]
---
# Description
[Evocative description of the holiday's atmosphere and importance.]

# Origins
[Detailed mythological or historical account.]

# Celebrations
[Step-by-step description of how the holiday unfolds.]

## Preparation
[What people do beforehand.]

## The Day Itself
[Main events, ceremonies, gatherings.]

## Aftermath
[How it ends, any lingering effects.]

# Regional Variations
[How different places or cultures celebrate it differently.]

# Stories & Legends
[Folktales associated with the holiday.]

# In the Game
[Mechanical benefits, adventure hooks, encounters that might occur during this time.]

# Notes