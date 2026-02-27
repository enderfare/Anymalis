---
title: "{{title}}"
subtitle: "*{{motto}}*"
image: "{{image}}"
tags: [Faction, Organization]
Type: "{{type}}"  # e.g., Guild, Cult, Family, Order
Leader: "{{leader}}"
LeaderTitle: "{{title}}"
Headquarters: "{{hq}}"
Founded: "{{founded}}"
Founder: "{{founder}}"
Status: "{{status}}"  # Active, Defunct, Secret
Membership: "{{membership}}"
NotableMembers: [Member1, Member2]
Allies: [Ally1]
Enemies: [Enemy1]
Goals: "{{goals}}"

layout:
  - type: header
    text: "Overview"
    above: Type
  - type: group
    keys: [Type, Leader, LeaderTitle, Headquarters]
  - type: separator
    above: Founded
  - type: group
    keys: [Founded, Founder, Status, Membership]
  - type: header
    text: "Relations"
    above: NotableMembers
  - type: group
    keys: [NotableMembers, Allies, Enemies]
---
# Description
[What the faction is known for, public perception.]

# History
[Origin, major events, evolution.]

# Goals & Methods
[What they want and how they operate.]

# Structure
[Hierarchy, ranks, initiation.]

# Notable Members
<figure style="float: left; width: 200px;">
  <img src="{{image}}" style="width:100%">
  <figcaption>[[Name]], [role]</figcaption>
</figure>

*(More members listed below.)*

# Bases & Holdings
[Key locations, assets.]

# Relationships
[With other factions, species, governments.]

# Secrets
||Hidden information, true agenda.||

# Adventure Hooks
[How the party might interact with them.]