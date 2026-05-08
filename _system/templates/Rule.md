---
title: "{{title}}"
subtitle: "*{{category}}*"
image: "{{image}}"
tags: [Rule, System]

# Metadata
Category: "{{category}}"               # e.g., Core Rule, Variant Rule, Optional Rule
System: "{{system}}"                    # e.g., Glyphic Resonance, D&D 5e
Source: "{{source}}"                    # e.g., Homebrew, [[Book Name]]
Status: "{{status}}"                    # e.g., Final, Playtest, Draft
Replaces: "{{replaces}}"                 # If it replaces an existing rule

# Usage
Prerequisites: "{{prereq}}"
AppliesTo: "{{applies_to}}"              # e.g., All characters, Only GMs
Optional: "{{optional}}"                 # Yes/No

layout:
  - type: header
    text: "Rule Info"
    above: Category
  - type: group
    keys: [Category, System, Source, Status, Replaces]

  - type: header
    text: "Usage"
    above: Prerequisites
  - type: group
    keys: [Prerequisites, AppliesTo, Optional]
---
# Description
[Brief explanation of what this rule covers.]

# Core Concept
[The design intent behind the rule.]

# The Rule
[Detailed mechanics. Use bullet points, examples, and tables as needed.]

## Subsection (if needed)
...

# Examples
- Example 1
- Example 2

# Interactions with Other Rules
[How this rule interacts with core mechanics or other rules.]

# Variants
[Optional tweaks or alternative implementations.]

# Design Notes
[Why this rule exists, what problem it solves.]

# Playtest Notes
[Feedback and adjustments.]

# Notes