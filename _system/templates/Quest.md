---
title: "{{title}}"
subtitle: "*{{type}} – Tier {{tier}}*"
image: "{{image}}"
tags: [Quest]

# Overview
Type: "{{type}}"                       # e.g., Main Story, Side, Personal, Faction
Tier: "{{tier}}"                        # 1-5 (Glyphic Resonance adventuring tier)
Status: "{{status}}"                    # e.g., Available, Active, Completed, Failed
Giver: "{{giver}}"                      # NPC or faction offering it
Location: "{{location}}"
SuggestedPartySize: "{{party_size}}"

# Rewards
RewardXP: "{{xp}}"
RewardGold: "{{gold}}"
RewardItems: "{{items}}"
RewardReputation: "{{reputation}}"       # With which faction
RewardOther: "{{other}}"

# Requirements
Prerequisites: "{{prereq}}"
TimeLimit: "{{time_limit}}"

# Related
FollowUpQuests: "{{followup}}"
ConflictsWith: "{{conflicts}}"

layout:
  - type: header
    text: "Quest Info"
    above: Type
  - type: group
    keys: [Type, Tier, Status, Giver, Location, SuggestedPartySize]

  - type: header
    text: "Rewards"
    above: RewardXP
  - type: group
    keys: [RewardXP, RewardGold, RewardItems, RewardReputation, RewardOther]

  - type: header
    text: "Requirements"
    above: Prerequisites
  - type: group
    keys: [Prerequisites, TimeLimit]

  - type: header
    text: "Related"
    above: FollowUpQuests
  - type: group
    keys: [FollowUpQuests, ConflictsWith]
---
# Description
[Brief summary of the quest hook.]

# Background
[Context: why the quest exists, what led to this situation.]

# Objectives
- [ ] Objective 1: [Description]
- [ ] Objective 2: [Description]
- [ ] Optional: [Description]

# Detailed Path
[Step-by-step breakdown of likely encounters, locations, and NPCs.]

## Stage 1: [Title]
[Details, possible approaches, DCs, NPCs.]

## Stage 2: [Title]
[Details...]

# Antagonists
[Key enemies or obstacles.]

# Allies
[Potential allies the party can make.]

# Complications
[Twists, betrayals, moral dilemmas.]

# Resolution Options
[Different outcomes based on player choices.]

# Aftermath
[How the world changes after quest completion.]

# Notes