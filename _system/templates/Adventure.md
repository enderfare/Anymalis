---
title: "{{title}}"
subtitle: "*{{arc_type}} – Tiers {{tier_range}}*"
image: "{{image}}"
tags: [Adventure, StoryArc]

# Overview
ArcType: "{{arc_type}}"                 # e.g., Campaign, Chapter, One-Shot
TierRange: "{{tier_range}}"              # e.g., 1-3, 3-5
Status: "{{status}}"                     # e.g., Planned, Active, Completed
Setting: "{{setting}}"                   # Where it takes place

# Structure
NumberofQuests: "{{quest_count}}"
EstimatedSessions: "{{sessions}}"
EstimatedPlaytime: "{{playtime}}"        # e.g., 20 hours

# Themes
CoreTheme: "{{theme}}"
MainVillain: "{{villain}}"
CentralConflict: "{{conflict}}"

# Rewards
MajorRewards: "{{rewards}}"               # e.g., Artifacts, Land, Titles

# Related
PrecedingAdventure: "{{prequel}}"
SequelAdventure: "{{sequel}}"

layout:
  - type: header
    text: "Adventure Info"
    above: ArcType
  - type: group
    keys: [ArcType, TierRange, Status, Setting]

  - type: header
    text: "Structure"
    above: NumberofQuests
  - type: group
    keys: [NumberofQuests, EstimatedSessions, EstimatedPlaytime]

  - type: header
    text: "Themes"
    above: CoreTheme
  - type: group
    keys: [CoreTheme, MainVillain, CentralConflict]

  - type: header
    text: "Rewards & Continuity"
    above: MajorRewards
  - type: group
    keys: [MajorRewards, PrecedingAdventure, SequelAdventure]
---
# Synopsis
[Brief summary of the overall story.]

# Background
[World context, events leading up to the adventure.]

# Adventure Overview
[High-level description of the arc's flow.]

# Quests
List each quest in the arc with links or brief descriptions:
1. [[Quest 1]] – [summary]
2. [[Quest 2]] – [summary]
...

# Key NPCs
- [[Name]] – [role]

# Major Locations
- [[Location]]

# Themes & Tone
[What the adventure explores, emotional beats.]

# Villain Details
[In-depth profile of the main antagonist.]

# Pacing Guide
[Advice on how to pace the adventure across sessions.]

# Conclusion & Aftermath
[How the arc ends, potential long-term consequences.]

# Notes