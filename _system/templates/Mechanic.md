---
title: "{{title}}"
subtitle: "*{{mechanic_type}}*"
image: "{{image}}"
tags: [Mechanic, Subsystem]

# Metadata
MechanicType: "{{mechanic_type}}"      # e.g., Skill, Combat Maneuver, Crafting, Downtime
System: "{{system}}"                    # e.g., Glyphic Resonance, D&D 5e
Source: "{{source}}"                    # e.g., Homebrew, [[Book Name]]
Status: "{{status}}"                    # e.g., Final, Playtest, Draft

# Usage
Prerequisites: "{{prereq}}"
ResourceCost: "{{resource_cost}}"       # e.g., Uses Animent, Stamina, etc.
ActivationTime: "{{activation}}"         # e.g., Action, Bonus Action, 1 hour
Duration: "{{duration}}"
Range: "{{range}}"

layout:
  - type: header
    text: "Mechanic Info"
    above: MechanicType
  - type: group
    keys: [MechanicType, System, Source, Status]

  - type: header
    text: "Usage"
    above: Prerequisites
  - type: group
    keys: [Prerequisites, ResourceCost, ActivationTime, Duration, Range]
---
# Description
[What this mechanic represents in the game world.]

# Mechanics
[Step-by-step instructions on how to use it.]

## Resolution
[How success/failure is determined.]

## Effects
[What happens on success, failure, or critical outcomes.]

# Examples
- Example of use in play.

# Scaling / Progression
[How it improves with character advancement.]

# Optional Rules
[Variations or additional depth.]

# Design Notes
[Intent and balance considerations.]

# Notes