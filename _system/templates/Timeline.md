---
title: "{{title}}"
subtitle: "*{{date}}*"
tags: [Event, Timeline]
Year: "{{year}}"
Era: "{{era}}"
Date: "{{date}}"
Location: "{{location}}"
Participants: [Participant1, Participant2]
Outcome: "{{outcome}}"
Significance: "{{significance}}"
RelatedEvents: [Event1, Event2]

layout:
  - type: header
    text: "Event Details"
    above: Year
  - type: group
    keys: [Year, Era, Date, Location]
  - type: separator
    above: Participants
  - type: group
    keys: [Participants, Outcome, Significance]
---
# Description
[What happened.]

# Background
[Context, causes.]

# The Event
[Narrative, key moments.]

# Aftermath
[Consequences, long-term effects.]

# Key Figures
- [[Name]] – role

# Gallery
<div class="gallery">
  <figure>![[image.jpg]]<figcaption>caption</figcaption></figure>
</div>