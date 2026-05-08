---
title: "Session {{number}}: {{title}}"
subtitle: "*{{date}}*"
image: "{{image}}"
tags: [SessionLog, AdventureLog]

# Metadata
SessionNumber: "{{number}}"
DatePlayed: "{{date_played}}"
Duration: "{{duration}}"              # e.g., 4 hours
Party: "{{party}}"                    # List of character names
GM: "{{gm}}"
System: "{{system}}"                  # e.g., Glyphic Resonance, D&D 5e

# Summary
PreviousSession: "{{previous}}"
NextSession: "{{next}}"
LocationsVisited: "{{locations}}"
NPCsMet: "{{npcs}}"
EnemiesEncountered: "{{enemies}}"

# Rewards
XPgained: "{{xp}}"
GoldGained: "{{gold}}"
ItemsFound: "{{items}}"
ImportantClues: "{{clues}}"

layout:
  - type: header
    text: "Session Info"
    above: SessionNumber
  - type: group
    keys: [SessionNumber, DatePlayed, Duration, Party, GM, System]

  - type: header
    text: "Summary"
    above: PreviousSession
  - type: group
    keys: [PreviousSession, NextSession, LocationsVisited, NPCsMet, EnemiesEncountered]

  - type: header
    text: "Rewards"
    above: XPgained
  - type: group
    keys: [XPgained, GoldGained, ItemsFound, ImportantClues]
---
# Recap
[Brief summary of the session's events, written in a narrative style.]

# Detailed Log
[In-depth account, scene by scene. Use bullet points or paragraphs.]

## Scene 1: [Title]
[What happened, decisions made, rolls that stood out.]

## Scene 2: [Title]
...

# Key Moments
- [Memorable quotes, critical successes/failures, character development.]

# Player Notes
[Decisions, alliances formed, unresolved threads.]

# GM Notes
[Behind-the-scenes thoughts, things to prepare for next time.]

# To-Do for Next Session
- [ ] Prep [encounter/NPC/location]
- [ ] Follow up on [player action]
- [ ] ...

# Handouts / Maps
[Links to images, documents shared during the session.]

# Notes