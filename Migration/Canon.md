# Anymalis Canon & Migration Control

> **Purpose:** Master control document for the Anymalis canon, repository migration, file ownership, consolidation, and replacement workflow.
>
> This document defines **canon precedence, historical-source handling, file ownership, consolidation principles, and migration safeguards.** It is a control reference, not a replacement for the source lore or rules.
>
> It is a planning and control document. It does not itself replace the detailed lore or rules contained in the referenced files.

---

# 1. Canon Hierarchy

When two files conflict, use the following priority order:

1. **Current `Lore/`**
2. **Current `Magic System/`**
3. **Current `Rules/`**
4. **`Examples/`**
5. **`Lineages (Simple) Outdated/`**

The exception is when a newer migration decision explicitly supersedes an older file.

## 1.1 Current Canon

The following directories contain the primary working canon:

```text
Lore/
Magic System/
Rules/
```

These should be treated as authoritative unless a contradiction is explicitly identified and resolved.

## 1.2 Supporting Material

```text
Examples/
```

Examples demonstrate intended usage but do not override formal rules.

If an example contradicts a formal rule, the formal rule takes precedence and the example must eventually be corrected.

## 1.3 Historical Material

```text
Lineages (Simple) Outdated/
```

This directory contains historical versions of the setting and mechanics.

It is useful for recovering:

- older lore
- discarded concepts
- previous lineage structures
- previous terminology
- cultural details
- Variant relationships
- potential ideas that may later be deliberately revived

It must **not** be treated as current canon automatically.

## 1.4 System Material

```text
_system/
```

System files control repository architecture, migration, naming, and canon management.

They describe how the project is organized rather than being ordinary in-world lore.

## 1.5 External System Material

```text
_system/templates
```

This is currently a Git submodule.

Its contents have not been ingested into the Anymalis canon and should not be assumed to be available when making canon decisions.

---

# 2. Core Canon Principles

## 2.1 Resonance

Anymalis uses **Glyphic Resonance / Elemental Resonance**.

Resonance is shaped through:

- Glyphs
- bodies
- conductive materials
- specialized techniques
- constructed magical systems

A Glyph is a structured method of shaping Resonance.

A complete magical construction combines multiple components to produce a spell effect.

---

# 3. Elemental Structure

Anymalis currently has **11 Elements**.

```text
Primordial
├── Light
├── Darkness
├── Time
└── Death

Fundamental
├── Life
└── Matter

Physical
├── Temperature
└── Fire

Terrestrial
├── Water
├── Earth
└── Wind
```

## 3.1 Element / Variant Hierarchy

```text
Element
└── Variant
```

A Variant belongs to exactly one Element.

Spells may combine multiple Elements, but combining Elements does **not** create a new hybrid Element.

## 3.2 Variant Counts

| Element | Variants |
|---|---:|
| Light | 2 |
| Darkness | 2 |
| Time | 3 |
| Death | 3 |
| Life | 4 |
| Matter | 5 |
| Temperature | 6 |
| Fire | 7 |
| Water | 8 |
| Earth | 9 |
| Wind | 10 |

The exact Variant definitions belong in:

```text
Magic System/Elements/
Magic System/Elements/Sub-Elements/
```

They should not be duplicated inside lineage files.

---

# 4. Meta-Glyphs

Anymalis currently recognizes two Meta-Glyphs:

```text
Prima
Nihil
```

## Prima

Represents:

- possibility
- creation

## Nihil

Represents:

- cancellation
- denial
- annihilation

Neither Meta-Glyph is automatically superior to ordinary magic.

Equivalent constructions can contest one another depending on:

- construction
- circumstances
- resolution

---

# 5. Spell Construction

The current conceptual construction is:

```text
WHAT?
Element

WHICH EXPRESSION?
Variant

HOW DOES IT BEHAVE?
Borders

HOW IMPORTANT IS THE GLYPH?
Foundation

HOW IS IT CONDUCTED?
Ink / Animen / Resonant Threads

WHERE DOES IT MANIFEST?
Surface

WHAT DOES THE COMPLETE CONSTRUCTION DO?
Spell Effect
```

The final authoritative implementation must be consolidated into:

```text
Magic System/Construction/Spell Construction.md
```

and related component files.

---

# 6. Current Spell Construction Components

Known construction components include:

```text
Foundation
Flow
Amplification
Precision
Duration
Trigger
Containment
Transformation
Connection
Resonance
Echo
Anchor
Veil
Pulse
Fracture
```

These belong to:

```text
Magic System/Outlines/
```

before being duplicated elsewhere.

---

# 7. Conductors

Known Resonance conductors:

```text
Conductive Ink
Animen
Sericari Resonant Threads
```

Relevant source files:

```text
Magic System/Inks/
Lore/Lineages/Sericari.md
```

Final conductor rules should be consolidated into:

```text
Magic System/Construction/Conductors.md
```

---

# 8. Known Inks

Current known inks:

```text
Silverthread
Ember Ash
Verdant Sap
Hollow Ink
Glasswater
```

Source directory:

```text
Magic System/Inks/
```

The existing individual ink files must be inspected before creating or consolidating:

```text
Magic System/Construction/Inks.md
```

The consolidated file should define shared ink rules.

Individual ink files should retain individual properties where appropriate.

---

# 9. Resonant Scars

Every naturally magical individual normally possesses a **Resonant Scar**.

A Resonant Scar normally encodes:

```text
Element
+
Specific Variant
```

The Scar determines natural Elemental Affinity.

Affinity can provide:

- reduced Resonance consumption
- easier stabilization
- improved precision
- instinctive understanding
- resistance to backlash

Possible Scar evolution mechanisms include:

- trauma
- near-death experiences
- ancient rituals
- Resonance overload

The authoritative rule must eventually be consolidated into:

```text
Magic System/Core/Resonant Scar.md
```

and integrated with:

```text
Rules/Character/Resonant Scar.md
```

These two files must have distinct responsibilities.

---

# 10. Glyph Fatigue

Glyph Fatigue is separate from SAN.

It represents physical, magical, and metaphysical strain from manipulating Resonance through a naturally magical body.

Known symptoms include:

- shaking
- blurred vision
- glowing veins
- temporary elemental-control loss
- physical instability
- metaphysical instability

Extreme overuse may create:

```text
Hollows
```

The existing mechanics are incomplete.

Before creating the final file, inspect:

```text
Magic System/Core Principles.md
Rules/
Examples/
```

The final system should be consolidated into:

```text
Magic System/Core/Glyph Fatigue.md
```

with character-facing integration handled elsewhere.

---

# 11. SAN

SAN represents:

```text
Mental / Psychological Stability
```

It is separate from:

```text
Glyph Fatigue
Resonance Stability
```

These three concepts must not be merged.

---

# 12. Resonance Stability

Resonance Stability is currently underdefined.

It must eventually establish:

- what RST represents
- how RST is calculated
- what affects it
- how it is tested
- how it recovers
- how Fracture interacts with it
- how character progression affects it

Candidate final file:

```text
Magic System/Core/Resonance Stability.md
```

---

# 13. Four Paths

Anymalis currently has four Paths:

```text
Scribe
Channeler
Artificer
Null
```

## Scribe

Focus:

- Glyph construction
- magical design
- versatility
- preparation
- control
- complex constructions

## Channeler

Focus:

- direct Resonance manipulation
- speed
- physical enhancement
- close combat
- anti-mage pressure

## Artificer

Focus:

- Resonance engineering
- devices
- tools
- equipment
- preparation

Artificers do not require Elemental Affinity.

## Null

Focus:

- anti-Resonance specialization

The word `Null` also describes natural, damaged, or severed magical signatures and conditions.

It is therefore not exclusively a species or school.

---

# 14. Character Structure

Current attributes:

```text
Might
Finesse
Endurance
Intellect
Insight
Presence
```

Current character-system concepts include:

```text
Attributes
Skills
Specializations
Techniques
Traits
Backgrounds
Lineages
Paths
Path Abilities
Advancement
Resonant Scar
Biological statistics
Social statistics
```

These must be given clear ownership before lineage migration begins.

---

# 15. Advancement

Current advancement model:

```text
Practice
   ↓
Instruction
   ↓
Experience
   ↓
Mastery
   ↓
Transformation
```

This should become the foundation for:

```text
Rules/Character/Advancement.md
```

and should not be duplicated across:

```text
Rules/Character/Character Creation.md
Rules/Integration/Character-Creation.md
Rules/Paths/
Rules/Skills/
```

---

# 16. Skill / Trait / Technique Boundaries

These concepts must remain distinct.

```text
Attribute
   ↓
Skill
   ↓
Specialization
```

A:

```text
Trait
```

is not automatically a Technique.

A:

```text
Technique
```

is not automatically a Skill.

A:

```text
Background
```

is not a Lineage.

The final definitions must be consolidated before lineage mechanics are rebuilt.

---

# 17. Social System

The current social distinction is:

```text
Skill      = what you can do
Renown     = how many people know you
Reputation = what they think
Tags       = what they associate with you
Rumors     = what they believe
```

These concepts must remain separate.

Expected authoritative files:

```text
Rules/Social/Renown.md
Rules/Social/Reputation.md
Rules/Social/Tags.md
Rules/Social/Rumors.md
Rules/Social/Social Integration.md
```

Existing files must be inspected before replacement.

---

# 18. Sericari Canon

Sericari are arachnid/humanoid **silkborn**.

Their identity is strongly associated with:

- silk
- Resonance
- craft
- cultivation
- Resonant Threads
- Living Looms
- the First Thread
- woven Glyphs
- silk architecture

Current structural model:

```text
Sericari
   ↓
Silk-Lineage
   ↓
Individual
```

However:

```text
Silk-Lineage
```

does **not** replace the individual's Resonant Scar.

The current model is:

```text
Silk-Lineage
    ↓
cultural / biological Elemental tradition

Resonant Scar
    ↓
individual Element + Variant

Individual
    ↓
Path + Skills + Techniques + Experiences + Beliefs
```

---

# 19. Sericari Silk-Lineages

Known historical Silk-Lineages:

```text
Umbrasilk
Graveweaver
Stonecoil
Embercoil
Verdant
Lumithread
Structureweaver
Thermoweaver
Chronothread
Tidewoven
Stormthread
```

Their associated Elements are:

| Silk-Lineage | Element |
|---|---|
| Umbrasilk | Darkness |
| Graveweaver | Death |
| Stonecoil | Earth |
| Embercoil | Fire |
| Verdant | Life |
| Lumithread | Light |
| Structureweaver | Matter |
| Thermoweaver | Temperature |
| Chronothread | Time |
| Tidewoven | Water |
| Stormthread | Wind |

These are **historical source structures that will be migrated into the new architecture**.

They should not automatically recreate their old mechanics.

---

# 20. Embercoil Migration Rule

Historical Embercoil contains seven Fire Variants:

```text
Flame
Ember
Blaze
Cinder
Spark
Wildfire
Hearth
```

Current Fire Variant files already exist at:

```text
Magic System/Elements/Sub-Elements/Fire/Blaze.md
Magic System/Elements/Sub-Elements/Fire/Cinder.md
Magic System/Elements/Sub-Elements/Fire/Ember.md
Magic System/Elements/Sub-Elements/Fire/Flame.md
Magic System/Elements/Sub-Elements/Fire/Hearth.md
Magic System/Elements/Sub-Elements/Fire/Spark.md
Magic System/Elements/Sub-Elements/Fire/Wildfire.md
```

Therefore the new Embercoil files must **reference those Variant files rather than duplicate their rules**.

---

# 21. Lineage Architecture

Every migrated lineage should eventually have two layers.

## Lore

```text
Lore/Lineages/[Lineage].md
```

Contains:

- identity
- biology
- culture
- history
- worldview
- traditions
- social structures
- relationships
- environmental adaptation
- narrative context

## Rules

```text
Rules/Character/Lineages/[Lineage].md
```

Contains:

- mechanical benefits
- mechanical restrictions
- character creation effects
- traits
- relevant biological rules
- available options
- references to the relevant Lore

For Sericari Silk-Lineages:

```text
Lore/Lineages/Sericari/[Silk-Lineage].md
Rules/Character/Lineages/Sericari/[Silk-Lineage].md
```

---

# 22. Lineage Rule

Whenever a new file is created under:

```text
Rules/Character/Lineages/
```

a corresponding Lore file must also exist under:

```text
Lore/Lineages/
```

For example:

```text
Rules/Character/Lineages/Sericari/Embercoil.md
Lore/Lineages/Sericari/Embercoil.md
```

No new lineage rules file should be created without its corresponding Lore file.

---

# 23. Base Lineages

Known base lineages requiring eventual migration:

```text
Corveki
Drifters
Felinnari
Sericari
```

Each requires:

```text
Lore/Lineages/Corveki.md
Rules/Character/Lineages/Corveki.md

Lore/Lineages/Drifters.md
Rules/Character/Lineages/Drifters.md

Lore/Lineages/Felinnari.md
Rules/Character/Lineages/Felinnari.md

Lore/Lineages/Sericari.md
Rules/Character/Lineages/Sericari.md
```

---

# 24. Conditions and Afflictions

Illuminated is currently treated as a condition/affliction rather than a conventional lineage.

Current authoritative lore:

```text
Lore/Lineages/Afflictions/Illuminated.md
```

Historical source:

```text
Lineages (Simple) Outdated/Afflictions/Luminaris.md
```

The old Luminaris material must not override the newer Illuminated model.

A future rules structure should distinguish:

```text
Conditions
Afflictions
Lineages
```

rather than treating all three as interchangeable.

---

# 25. Rimekin

Current Rimekin material:

```text
Lore/Clans/Water/Rimekin.md
Clans/Water/Rimekin.md
```

Rimekin are Water-associated and centered around Frost.

Important migration issue:

Current Water Variants are:

```text
Flow
Still
Tide
Rain
Ice
Mist
Deep
Spring
```

There is currently no obvious:

```text
Frost
```

Variant.

This contradiction must be resolved before the final Rimekin rules are produced.

Do not silently invent a resolution.

---

# 26. Migration Phases

The migration should proceed in the following order.

---

## Phase 0 — Canon & Repository Architecture

### Create / consolidate

```text
_system/Canon.md
_system/Architecture.md
_system/Naming Conventions.md
_system/Migration.md
```

### Inspect

```text
Lore/
Magic System/
Rules/
Examples/
Lineages (Simple) Outdated/
_system/
```

### Goal

Establish:

- canon hierarchy
- file ownership
- naming conventions
- migration rules
- historical boundaries
- duplication policy

---

# 27. Phase 1 — Rules Foundation

Before creating lineage rules, consolidate the existing character/rules foundation.

Expected files:

```text
Rules/Core/Core Rules.md
Rules/Core/Terminology.md
Rules/Character/Attributes.md
Rules/Character/Derived Statistics.md
Rules/Character/Resources.md
Rules/Character/Checks.md
```

Before creating them, inspect:

```text
Rules/Core/
Rules/Character/
Rules/Skills/
Rules/Integration/
Rules/Paths/
Rules/Social/
Rules/Biology/
```

Goal:

Create one authoritative foundation instead of creating parallel versions of existing rules.

---

# 28. Phase 2 — Skills and Character Components

Expected files:

```text
Rules/Character/Skills.md
Rules/Character/Specializations.md
Rules/Character/Techniques.md
Rules/Character/Traits.md
Rules/Character/Backgrounds.md
Rules/Character/Advancement.md
```

Inspect before creating:

```text
Rules/Skills/
Rules/Character/
Rules/Integration/
Examples/Character/
Examples/Character/Character-Sheet.md
```

Particular duplication risks:

```text
Rules/Character/Techniques.md
Rules/Skills/Techniques.md
```

These must be consolidated rather than maintained as two competing authoritative files.

---

# 29. Phase 3 — Character Creation

Expected authoritative files:

```text
Rules/Character/Character Creation.md
Rules/Integration/Character-Creation.md
```

These currently overlap conceptually.

The final architecture must decide which is the authoritative procedure and which, if retained, serves as integration/reference material.

Inspect:

```text
Rules/Character/Character Creation.md
Rules/Integration/Character-Creation.md
Rules/Character/Lineages.md
Rules/Character/Traits.md
Rules/Character/Skills.md
Rules/Character/Techniques.md
Rules/Character/Backgrounds.md
Rules/Character/Advancement.md
Examples/Character/Character-Sheet.md
```

---

# 30. Phase 4 — Biology

Expected files:

```text
Rules/Biology/ATS.md
Rules/Biology/HTS.md
Rules/Biology/Quimera Percentage.md
Rules/Biology/Biological Traits.md
```

Inspect all existing biological/statistical rules before creating these.

Known issue:

```text
Q% = ATS × 5 + HTS × 3 + RES / 10
```

may exceed 100 and currently lacks a clear cap/normalization procedure.

This must be resolved rather than silently preserved.

---

# 31. Phase 5 — Paths

Expected files:

```text
Rules/Paths/Four Paths.md
Rules/Paths/Path Skills.md
Rules/Paths/Path Abilities.md
Rules/Paths/Path Integration.md
```

Inspect:

```text
Rules/Paths/
Lore/The Four Paths.md
Rules/Character/
```

The final system must clearly separate:

```text
Path identity
Path mechanics
Path abilities
Path integration
```

---

# 32. Phase 6 — Social System

Expected files:

```text
Rules/Social/Renown.md
Rules/Social/Reputation.md
Rules/Social/Tags.md
Rules/Social/Rumors.md
Rules/Social/Social Integration.md
```

Inspect:

```text
Rules/Social/
Rules/Character/
Rules/Integration/
```

Do not merge Renown, Reputation, Tags, and Rumors into a single vague reputation statistic.

---

# 33. Phase 7 — Magic Foundation

Expected files:

```text
Magic System/Core/Resonance.md
Magic System/Core/Glyphs.md
Magic System/Core/Resonant Scar.md
Magic System/Core/Resonance Stability.md
Magic System/Core/Glyph Fatigue.md

Magic System/Construction/Spell Construction.md
Magic System/Construction/Foundation.md
Magic System/Construction/Borders.md
Magic System/Construction/Conductors.md
Magic System/Construction/Surfaces.md
Magic System/Construction/Inks.md

Magic System/Meta-Glyphs/Prima.md
Magic System/Meta-Glyphs/Nihil.md
```

Inspect first:

```text
Magic System/Core Principles.md
Magic System/Spell Construction.md
Magic System/Outlines/
Magic System/Inks/
Magic System/Elements/
Magic System/Elements/Sub-Elements/
Rules/
Examples/Spell Construction Examples.md
```

Known contradictions to resolve:

1. Foundation wording
2. Transformation wording
3. Resonance Stability
4. Glyph Fatigue
5. Ink affinity bonuses
6. Spell construction completeness
7. D&D terminology leakage

---

# 34. Phase 8 — Outlines

Expected files:

```text
Magic System/Outlines/Foundation.md
Magic System/Outlines/Flow.md
Magic System/Outlines/Amplification.md
Magic System/Outlines/Precision.md
Magic System/Outlines/Duration.md
Magic System/Outlines/Trigger.md
Magic System/Outlines/Containment.md
Magic System/Outlines/Transformation.md
Magic System/Outlines/Connection.md
Magic System/Outlines/Resonance.md
Magic System/Outlines/Echo.md
Magic System/Outlines/Anchor.md
Magic System/Outlines/Veil.md
Magic System/Outlines/Pulse.md
Magic System/Outlines/Fracture.md
```

Existing files must be inspected before creating replacements.

---

# 35. Phase 9 — Elements and Variants

Expected structure:

```text
Magic System/Elements/Light/
Magic System/Elements/Darkness/
Magic System/Elements/Time/
Magic System/Elements/Death/
Magic System/Elements/Life/
Magic System/Elements/Matter/
Magic System/Elements/Temperature/
Magic System/Elements/Fire/
Magic System/Elements/Water/
Magic System/Elements/Earth/
Magic System/Elements/Wind/
```

Variant files should be placed beneath their owning Element.

Existing Variant files must be preserved where they are already authoritative.

Do not recreate existing Fire Variant files merely to support Embercoil.

---

# 36. Phase 10 — Base Lineages

Migrate only after the preceding foundations are stable.

### Drifters

```text
Lore/Lineages/Drifters.md
Rules/Character/Lineages/Drifters.md
```

Historical source:

```text
Lineages (Simple) Outdated/Drifters.md
```

### Sericari

```text
Lore/Lineages/Sericari.md
Rules/Character/Lineages/Sericari.md
```

Historical/source material:

```text
Lineages (Simple) Outdated/Sericari.md
Lore/Lineages/Sericari.md
```

### Corveki

```text
Lore/Lineages/Corveki.md
Rules/Character/Lineages/Corveki.md
```

Historical source:

```text
Lineages (Simple) Outdated/Corveki.md
```

### Felinnari

```text
Lore/Lineages/Felinnari.md
Rules/Character/Lineages/Felinnari.md
```

Historical source:

```text
Lineages (Simple) Outdated/Felinnari.md
```

---

# 37. Phase 11 — Sericari Silk-Lineages

Each Silk-Lineage receives **two files**.

## Umbrasilk

```text
Lore/Lineages/Sericari/Umbrasilk.md
Rules/Character/Lineages/Sericari/Umbrasilk.md
```

Historical source:

```text
Lineages (Simple) Outdated/Sericari/Umbrasilk.md
```

## Graveweaver

```text
Lore/Lineages/Sericari/Graveweaver.md
Rules/Character/Lineages/Sericari/Graveweaver.md
```

Historical source:

```text
Lineages (Simple) Outdated/Sericari/Graveweaver.md
```

## Stonecoil

```text
Lore/Lineages/Sericari/Stonecoil.md
Rules/Character/Lineages/Sericari/Stonecoil.md
```

Historical source:

```text
Lineages (Simple) Outdated/Sericari/Stonecoil.md
```

## Embercoil

```text
Lore/Lineages/Sericari/Embercoil.md
Rules/Character/Lineages/Sericari/Embercoil.md
```

Historical source:

```text
Lineages (Simple) Outdated/Sericari/Embercoil.md
```

Variant dependencies:

```text
Magic System/Elements/Sub-Elements/Fire/Flame.md
Magic System/Elements/Sub-Elements/Fire/Ember.md
Magic System/Elements/Sub-Elements/Fire/Blaze.md
Magic System/Elements/Sub-Elements/Fire/Cinder.md
Magic System/Elements/Sub-Elements/Fire/Spark.md
Magic System/Elements/Sub-Elements/Fire/Wildfire.md
Magic System/Elements/Sub-Elements/Fire/Hearth.md
```

## Verdant

```text
Lore/Lineages/Sericari/Verdant.md
Rules/Character/Lineages/Sericari/Verdant.md
```

Historical source:

```text
Lineages (Simple) Outdated/Sericari/Verdant.md
```

## Lumithread

```text
Lore/Lineages/Sericari/Lumithread.md
Rules/Character/Lineages/Sericari/Lumithread.md
```

Historical source:

```text
Lineages (Simple) Outdated/Sericari/Lumithread.md
```

## Structureweaver

```text
Lore/Lineages/Sericari/Structureweaver.md
Rules/Character/Lineages/Sericari/Structureweaver.md
```

Historical source:

```text
Lineages (Simple) Outdated/Sericari/Structureweaver.md
```

## Thermoweaver

```text
Lore/Lineages/Sericari/Thermoweaver.md
Rules/Character/Lineages/Sericari/Thermoweaver.md
```

Historical source:

```text
Lineages (Simple) Outdated/Sericari/Thermoweaver.md
```

## Chronothread

```text
Lore/Lineages/Sericari/Chronothread.md
Rules/Character/Lineages/Sericari/Chronothread.md
```

Historical source:

```text
Lineages (Simple) Outdated/Sericari/Chronothread.md
```

## Tidewoven

```text
Lore/Lineages/Sericari/Tidewoven.md
Rules/Character/Lineages/Sericari/Tidewoven.md
```

Historical source:

```text
Lineages (Simple) Outdated/Sericari/Tidewoven.md
```

## Stormthread

```text
Lore/Lineages/Sericari/Stormthread.md
Rules/Character/Lineages/Sericari/Stormthread.md
```

Historical source:

```text
Lineages (Simple) Outdated/Sericari/Stormthread.md
```

---

# 38. Phase 12 — Conditions and Afflictions

Expected files:

```text
Rules/Conditions/Conditions.md
Rules/Conditions/Afflictions.md
Rules/Conditions/Illuminated.md
```

Lore:

```text
Lore/Lineages/Afflictions/Illuminated.md
```

Historical source:

```text
Lineages (Simple) Outdated/Afflictions/Luminaris.md
```

The condition system must be defined before expanding the Affliction catalogue.

---

# 39. Phase 13 — Lore Consolidation

Expected organizational targets:

```text
Lore/World/
Lore/World/History/
Lore/Cosmology/
Lore/Lineages/
Lore/Conditions/
Lore/Clans/
```

Existing material to inspect:

```text
Lore/The Resonance World.md
Lore/The Four Paths.md
Lore/Lineages/
Lore/Clans/
```

Goal:

Move lore into its final ownership structure without duplicating rules.

---

# 40. Phase 14 — Examples

Existing examples:

```text
Examples/Character/Character-Sheet.md
Examples/Character/Character Seraphine Vale.md
Examples/Spell Construction Examples.md
```

Expected future organization:

```text
Examples/Characters/
Examples/Spells/
Examples/Lineages/
```

Examples should be updated only after the rules they demonstrate have stabilized.

---

# 41. Phase 15 — Reference

Expected reference files:

```text
Reference/Elements.md
Reference/Variants.md
Reference/Lineages.md
Reference/Paths.md
Reference/Skills.md
Reference/Glossary.md
```

These are indexes/reference material.

They must not become competing sources of rules.

---

# 42. Phase 16 — Legacy Cleanup

Eventually move historical material into:

```text
Archive/Legacy/
```

The following directory is the primary migration source:

```text
Lineages (Simple) Outdated/
```

Before archiving, verify that all useful information has been deliberately classified as:

```text
Migrated
Superseded
Rejected
Pending
```

Nothing should disappear merely because it is old.

---

# 43. Known Contradictions Requiring Explicit Resolution

## 43.1 Rimekin / Frost

Current:

```text
Lore/Clans/Water/Rimekin.md
```

references Frost.

Current Water Variant structure:

```text
Magic System/Elements/Sub-Elements/Water/
```

does not currently contain an obvious Frost Variant.

Resolution must be explicit.

---

## 43.2 Foundation

Potential conflict between:

```text
Magic System/Core Principles.md
Magic System/Outlines/Core.md
```

The stronger intended interpretation appears to be:

```text
Core Glyph
    ↓
Element + Variant identity

Foundation
    ↓
importance / conceptual reinforcement
```

This must be formally settled in the consolidated construction rules.

---

## 43.3 Transformation

Core rules indicate that Element/Variant identity is fixed by the Core Glyph.

Transformation language may imply changing the elemental identity.

Final rules must distinguish:

```text
changing manifestation
```

from:

```text
changing Element / Variant identity
```

---

## 43.4 Foundation Missing From Examples

Core principles indicate Foundation is important to complete Glyph construction, while existing examples may omit it.

The final example format must match the final formal construction rules.

---

## 43.5 Resonance Stability

Current RST rules are insufficiently defined.

Do not create dependent mechanics until the underlying definition is stable.

---

## 43.6 Glyph Fatigue

Current concept is established but mechanical thresholds/recovery are incomplete.

Do not invent final numbers without deliberate system design.

---

## 43.7 Training

Existing formulas refer to:

```text
Training
```

but the current character system does not clearly establish one universal numerical Training statistic.

This must be resolved during Rules consolidation.

---

## 43.8 Legacy D&D Terminology

Existing files contain terminology such as:

```text
Proficiency Bonus
Spell Level
WIS Save
DEX Save
AC
Advantage
Disadvantage
Short Rest
Long Rest
HP
```

Each occurrence must be audited.

Some concepts may survive under Anymalis terminology; others should be replaced.

Do not mechanically preserve D&D terminology where it conflicts with the native Anymalis system.

---

## 43.9 Skill Mastery vs Proficiency

The current system contains:

```text
Skill Mastery Bonus
```

while some older files use:

```text
Proficiency Bonus
```

The final rules must select one coherent terminology and formula structure.

---

## 43.10 Ink Affinity Bonus

Element files contain:

```text
AffinityInkBonus
```

while character rules reference:

```text
Affinity Bonus
```

The connection between these concepts must be formally defined.

---

## 43.11 Quimera Percentage

Current formula:

```text
Q% = ATS × 5 + HTS × 3 + RES / 10
```

Potential issue:

```text
Q% > 100
```

may be possible.

A cap, normalization, or different formula must be deliberately established.

---

# 44. File-by-File Migration Matrix

| # | Final Path | Status | Inspect First | Migration Action |
|---:|---|---|---|---|
| 1 | `_system/Canon.md` | **Create** | `Lore/`, `Magic System/`, `Rules/`, `Examples/`, `Lineages (Simple) Outdated/` | Master canon/migration control |
| 2 | `_system/Architecture.md` | Create | `Lore/`, `Magic System/`, `Rules/`, `Examples/` | Define ownership |
| 3 | `_system/Naming Conventions.md` | Create | All existing filenames | Standardize names |
| 4 | `_system/Migration.md` | Create | Existing repository | Track migrations |
| 5 | `Rules/Core/Core Rules.md` | Consolidate | `Rules/Core/` | Establish core rules |
| 6 | `Rules/Core/Terminology.md` | Consolidate | `Rules/`, `Magic System/` | Establish vocabulary |
| 7 | `Rules/Character/Attributes.md` | Consolidate | `Rules/Character/` | Authoritative attributes |
| 8 | `Rules/Character/Checks.md` | Consolidate | `Rules/Character/`, `Rules/Core/` | Resolution mechanics |
| 9 | `Rules/Character/Derived Statistics.md` | Create/Consolidate | `Rules/Character/` | Derived values |
| 10 | `Rules/Character/Resources.md` | Create/Consolidate | `Rules/Character/`, `Magic System/` | Character resources |
| 11 | `Rules/Character/Skills.md` | Rebuild | `Rules/Character/Skills.md`, `Rules/Skills/` | Consolidate skill rules |
| 12 | `Rules/Character/Specializations.md` | Rebuild | `Rules/Character/`, `Rules/Skills/` | Define specialization |
| 13 | `Rules/Character/Techniques.md` | Rebuild | `Rules/Character/Techniques.md`, `Rules/Skills/Techniques.md` | Eliminate duplicate ownership |
| 14 | `Rules/Character/Traits.md` | Rebuild | `Rules/Character/Traits.md`, `Rules/Skills/`, `Rules/Integration/` | Define traits |
| 15 | `Rules/Character/Backgrounds.md` | Consolidate | `Rules/Character/`, `Rules/Integration/` | Define backgrounds |
| 16 | `Rules/Character/Advancement.md` | Create/Consolidate | `Rules/Character/`, `Rules/Paths/` | Practice → Transformation |
| 17 | `Rules/Character/Character Creation.md` | Rebuild | `Rules/Character/Character Creation.md`, `Rules/Integration/Character-Creation.md` | Single creation procedure |
| 18 | `Rules/Biology/ATS.md` | Create/Consolidate | `Rules/`, existing ATS references | ATS rules |
| 19 | `Rules/Biology/HTS.md` | Create/Consolidate | `Rules/`, existing HTS references | HTS rules |
| 20 | `Rules/Biology/Quimera Percentage.md` | Create/Consolidate | `Rules/`, existing Q% references | Resolve formula |
| 21 | `Rules/Biology/Biological Traits.md` | Create | `Rules/Character/`, `Rules/Biology/` | Biological framework |
| 22 | `Rules/Paths/Four Paths.md` | Consolidate | `Lore/The Four Paths.md`, `Rules/Paths/` | Path definitions |
| 23 | `Rules/Paths/Path Skills.md` | Create/Consolidate | `Rules/Paths/`, `Rules/Skills/` | Path skill relationships |
| 24 | `Rules/Paths/Path Abilities.md` | Consolidate | `Rules/Paths/` | Path mechanics |
| 25 | `Rules/Paths/Path Integration.md` | Create | `Rules/Paths/`, `Rules/Integration/` | Integrate Paths |
| 26 | `Rules/Social/Renown.md` | Consolidate | `Rules/Social/` | Renown |
| 27 | `Rules/Social/Reputation.md` | Consolidate | `Rules/Social/` | Reputation |
| 28 | `Rules/Social/Tags.md` | Consolidate | `Rules/Social/` | Tags |
| 29 | `Rules/Social/Rumors.md` | Consolidate | `Rules/Social/` | Rumors |
| 30 | `Rules/Social/Social Integration.md` | Create | `Rules/Social/`, `Rules/Integration/` | Social integration |
| 31 | `Magic System/Core/Resonance.md` | Consolidate | `Magic System/Core Principles.md`, `Magic System/`, `Rules/` | Resonance foundation |
| 32 | `Magic System/Core/Glyphs.md` | Consolidate | `Magic System/Core Principles.md`, `Magic System/` | Glyph framework |
| 33 | `Magic System/Core/Resonant Scar.md` | Create/Consolidate | `Magic System/Core Principles.md`, `Rules/` | Scar mechanics |
| 34 | `Magic System/Core/Resonance Stability.md` | Create | `Magic System/`, `Rules/` | Define RST |
| 35 | `Magic System/Core/Glyph Fatigue.md` | Create | `Magic System/`, `Rules/` | Define fatigue |
| 36 | `Magic System/Construction/Spell Construction.md` | Rebuild | `Magic System/Spell Construction.md`, `Examples/Spell Construction Examples.md` | Single construction framework |
| 37 | `Magic System/Construction/Foundation.md` | Consolidate | `Magic System/Outlines/Core.md`, `Magic System/Core Principles.md` | Resolve Foundation |
| 38 | `Magic System/Construction/Borders.md` | Consolidate | `Magic System/Outlines/`, `Magic System/Spell Construction.md` | Borders |
| 39 | `Magic System/Construction/Conductors.md` | Create/Consolidate | `Magic System/Inks/`, `Lore/Lineages/Sericari.md` | Conductors |
| 40 | `Magic System/Construction/Surfaces.md` | Create/Consolidate | `Magic System/`, `Rules/` | Surfaces |
| 41 | `Magic System/Construction/Inks.md` | Create/Consolidate | `Magic System/Inks/` | Shared ink framework |
| 42 | `Magic System/Meta-Glyphs/Prima.md` | Create/Consolidate | `Magic System/Core Principles.md` | Prima |
| 43 | `Magic System/Meta-Glyphs/Nihil.md` | Create/Consolidate | `Magic System/Core Principles.md` | Nihil |
| 44 | `Magic System/Outlines/Foundation.md` | Rebuild | `Magic System/Outlines/Core.md`, `Magic System/Core Principles.md` | Foundation |
| 45 | `Magic System/Outlines/Flow.md` | Consolidate | `Magic System/Outlines/` | Flow |
| 46 | `Magic System/Outlines/Amplification.md` | Consolidate | `Magic System/Outlines/` | Amplification |
| 47 | `Magic System/Outlines/Precision.md` | Consolidate | `Magic System/Outlines/` | Precision |
| 48 | `Magic System/Outlines/Duration.md` | Consolidate | `Magic System/Outlines/` | Duration |
| 49 | `Magic System/Outlines/Trigger.md` | Consolidate | `Magic System/Outlines/` | Trigger |
| 50 | `Magic System/Outlines/Containment.md` | Consolidate | `Magic System/Outlines/` | Containment |
| 51 | `Magic System/Outlines/Transformation.md` | Rebuild | `Magic System/Outlines/`, `Magic System/Core Principles.md` | Resolve identity conflict |
| 52 | `Magic System/Outlines/Connection.md` | Consolidate | `Magic System/Outlines/` | Connection |
| 53 | `Magic System/Outlines/Resonance.md` | Consolidate | `Magic System/Outlines/` | Resonance outline |
| 54 | `Magic System/Outlines/Echo.md` | Consolidate | `Magic System/Outlines/` | Echo |
| 55 | `Magic System/Outlines/Anchor.md` | Consolidate | `Magic System/Outlines/` | Anchor |
| 56 | `Magic System/Outlines/Veil.md` | Consolidate | `Magic System/Outlines/` | Veil |
| 57 | `Magic System/Outlines/Pulse.md` | Consolidate | `Magic System/Outlines/` | Pulse |
| 58 | `Magic System/Outlines/Fracture.md` | Rebuild | `Magic System/Outlines/`, `Magic System/Core Principles.md` | Resolve RST interaction |
| 59 | `Magic System/Elements/Light/` | Consolidate | Existing Light files | Element framework |
| 60 | `Magic System/Elements/Darkness/` | Consolidate | Existing Darkness files | Element framework |
| 61 | `Magic System/Elements/Time/` | Consolidate | Existing Time files | Element framework |
| 62 | `Magic System/Elements/Death/` | Consolidate | Existing Death files | Element framework |
| 63 | `Magic System/Elements/Life/` | Consolidate | Existing Life files | Element framework |
| 64 | `Magic System/Elements/Matter/` | Consolidate | Existing Matter files | Element framework |
| 65 | `Magic System/Elements/Temperature/` | Consolidate | Existing Temperature files | Element framework |
| 66 | `Magic System/Elements/Fire/` | Consolidate | Existing Fire files | Element framework |
| 67 | `Magic System/Elements/Water/` | Consolidate | Existing Water files | Element framework |
| 68 | `Magic System/Elements/Earth/` | Consolidate | Existing Earth files | Element framework |
| 69 | `Magic System/Elements/Wind/` | Consolidate | Existing Wind files | Element framework |
| 70 | `Lore/Lineages/Drifters.md` | Rebuild | `Lineages (Simple) Outdated/Drifters.md` | Lore migration |
| 71 | `Rules/Character/Lineages/Drifters.md` | Rebuild | `Lineages (Simple) Outdated/Drifters.md`, Rules foundation | Mechanics migration |
| 72 | `Lore/Lineages/Sericari.md` | Rebuild | `Lore/Lineages/Sericari.md`, `Lineages (Simple) Outdated/Sericari.md` | Lore migration |
| 73 | `Rules/Character/Lineages/Sericari.md` | Rebuild | `Lore/Lineages/Sericari.md`, Rules foundation | Mechanics migration |
| 74 | `Lore/Lineages/Corveki.md` | Rebuild | `Lineages (Simple) Outdated/Corveki.md` | Lore migration |
| 75 | `Rules/Character/Lineages/Corveki.md` | Rebuild | `Lineages (Simple) Outdated/Corveki.md`, Rules foundation | Mechanics migration |
| 76 | `Lore/Lineages/Felinnari.md` | Rebuild | `Lineages (Simple) Outdated/Felinnari.md` | Lore migration |
| 77 | `Rules/Character/Lineages/Felinnari.md` | Rebuild | `Lineages (Simple) Outdated/Felinnari.md`, Rules foundation | Mechanics migration |
| 78 | `Lore/Lineages/Sericari/Umbrasilk.md` | Rebuild | `Lineages (Simple) Outdated/Sericari/Umbrasilk.md` | Silk-Lineage lore |
| 79 | `Rules/Character/Lineages/Sericari/Umbrasilk.md` | Rebuild | same + Darkness Variants | Silk-Lineage mechanics |
| 80 | `Lore/Lineages/Sericari/Graveweaver.md` | Rebuild | `Lineages (Simple) Outdated/Sericari/Graveweaver.md` | Silk-Lineage lore |
| 81 | `Rules/Character/Lineages/Sericari/Graveweaver.md` | Rebuild | same + Death Variants | Silk-Lineage mechanics |
| 82 | `Lore/Lineages/Sericari/Stonecoil.md` | Rebuild | `Lineages (Simple) Outdated/Sericari/Stonecoil.md` | Silk-Lineage lore |
| 83 | `Rules/Character/Lineages/Sericari/Stonecoil.md` | Rebuild | same + Earth Variants | Silk-Lineage mechanics |
| 84 | `Lore/Lineages/Sericari/Embercoil.md` | Rebuild | `Lineages (Simple) Outdated/Sericari/Embercoil.md` | Silk-Lineage lore |
| 85 | `Rules/Character/Lineages/Sericari/Embercoil.md` | Rebuild | same + Fire Variants | Silk-Lineage mechanics |
| 86 | `Lore/Lineages/Sericari/Verdant.md` | Rebuild | `Lineages (Simple) Outdated/Sericari/Verdant.md` | Silk-Lineage lore |
| 87 | `Rules/Character/Lineages/Sericari/Verdant.md` | Rebuild | same + Life Variants | Silk-Lineage mechanics |
| 88 | `Lore/Lineages/Sericari/Lumithread.md` | Rebuild | `Lineages (Simple) Outdated/Sericari/Lumithread.md` | Silk-Lineage lore |
| 89 | `Rules/Character/Lineages/Sericari/Lumithread.md` | Rebuild | same + Light Variants | Silk-Lineage mechanics |
| 90 | `Lore/Lineages/Sericari/Structureweaver.md` | Rebuild | `Lineages (Simple) Outdated/Sericari/Structureweaver.md` | Silk-Lineage lore |
| 91 | `Rules/Character/Lineages/Sericari/Structureweaver.md` | Rebuild | same + Matter Variants | Silk-Lineage mechanics |
| 92 | `Lore/Lineages/Sericari/Thermoweaver.md` | Rebuild | `Lineages (Simple) Outdated/Sericari/Thermoweaver.md` | Silk-Lineage lore |
| 93 | `Rules/Character/Lineages/Sericari/Thermoweaver.md` | Rebuild | same + Temperature Variants | Silk-Lineage mechanics |
| 94 | `Lore/Lineages/Sericari/Chronothread.md` | Rebuild | `Lineages (Simple) Outdated/Sericari/Chronothread.md` | Silk-Lineage lore |
| 95 | `Rules/Character/Lineages/Sericari/Chronothread.md` | Rebuild | same + Time Variants | Silk-Lineage mechanics |
| 96 | `Lore/Lineages/Sericari/Tidewoven.md` | Rebuild | `Lineages (Simple) Outdated/Sericari/Tidewoven.md` | Silk-Lineage lore |
| 97 | `Rules/Character/Lineages/Sericari/Tidewoven.md` | Rebuild | same + Water Variants | Silk-Lineage mechanics |
| 98 | `Lore/Lineages/Sericari/Stormthread.md` | Rebuild | `Lineages (Simple) Outdated/Sericari/Stormthread.md` | Silk-Lineage lore |
| 99 | `Rules/Character/Lineages/Sericari/Stormthread.md` | Rebuild | same + Wind Variants | Silk-Lineage mechanics |
| 100 | `Rules/Conditions/Conditions.md` | Create | `Rules/`, `Lore/Lineages/Afflictions/Illuminated.md` | Conditions framework |
| 101 | `Rules/Conditions/Afflictions.md` | Create | `Rules/`, `Lore/Lineages/Afflictions/Illuminated.md` | Affliction framework |
| 102 | `Rules/Conditions/Illuminated.md` | Create | `Lore/Lineages/Afflictions/Illuminated.md`, `Lineages (Simple) Outdated/Afflictions/Luminaris.md` | Mechanical condition |
| 103 | `Lore/World/Resonance World.md` | Reorganize | `Lore/The Resonance World.md` | World lore |
| 104 | `Lore/Cosmology/The Four Paths.md` | Reorganize | `Lore/The Four Paths.md` | Cosmology/lore |
| 105 | `Examples/Characters/Character-Sheet.md` | Rebuild | `Examples/Character/Character-Sheet.md` | Update to final rules |
| 106 | `Examples/Characters/Seraphine Vale.md` | Rebuild | `Examples/Character/Character Seraphine Vale.md` | Update to final rules |
| 107 | `Examples/Spells/Spell Construction Examples.md` | Rebuild | `Examples/Spell Construction Examples.md` | Update to final spell rules |
| 108 | `Examples/Lineages/` | Create | All final lineage files | Provide canonical examples |
| 109 | `Reference/Elements.md` | Create | `Magic System/Elements/` | Element index |
| 110 | `Reference/Variants.md` | Create | `Magic System/Elements/Sub-Elements/` | Variant index |
| 111 | `Reference/Lineages.md` | Create | `Lore/Lineages/`, `Rules/Character/Lineages/` | Lineage index |
| 112 | `Reference/Paths.md` | Create | `Rules/Paths/`, `Lore/The Four Paths.md` | Path index |
| 113 | `Reference/Skills.md` | Create | `Rules/Character/Skills.md`, `Rules/Skills/` | Skill index |
| 114 | `Reference/Glossary.md` | Create | All final files | Global terminology index |
| 115 | `Archive/Legacy/` | Create | `Lineages (Simple) Outdated/` | Historical archive |

---

# 45. Existing Files That Must Be Audited Before New Files Are Created

The following paths are especially important because they contain material likely to overlap with future files.

## Character Rules

```text
Rules/Character/
Rules/Character/Character Creation.md
Rules/Character/Lineages.md
Rules/Character/Skills.md
Rules/Character/Traits.md
Rules/Character/Techniques.md
```

## Skills

```text
Rules/Skills/
Rules/Skills/Techniques.md
```

## Integration

```text
Rules/Integration/
Rules/Integration/Character-Creation.md
```

## Paths

```text
Rules/Paths/
```

## Social

```text
Rules/Social/
```

## Biology

```text
Rules/Biology/
```

## Magic

```text
Magic System/Core Principles.md
Magic System/Spell Construction.md
Magic System/Outlines/
Magic System/Inks/
Magic System/Elements/
Magic System/Elements/Sub-Elements/
```

## Lore

```text
Lore/The Resonance World.md
Lore/The Four Paths.md
Lore/Lineages/
Lore/Clans/
```

## Examples

```text
Examples/Character/Character-Sheet.md
Examples/Character/Character Seraphine Vale.md
Examples/Spell Construction Examples.md
```

## Historical Sources

```text
Lineages (Simple) Outdated/
Lineages (Simple) Outdated/Sericari/
Lineages (Simple) Outdated/Afflictions/
```

---

# 46. Duplication Prevention Rules

Before creating a new file:

1. Search the entire repository for the concept.
2. List every existing path containing relevant rules.
3. Determine whether the existing material should be:
   - retained
   - merged
   - split
   - renamed
   - moved
   - deprecated
4. Create only one authoritative owner.
5. Use links/references for secondary appearances.
6. Update examples after the authoritative rule changes.

Never create a second file simply because the existing file has a different folder.

---

# 47. Lore / Rules Separation

The following distinction is mandatory.

## Lore answers:

> What is this?

> Who are they?

> Where did it come from?

> How does it fit into the world?

> What do people believe about it?

## Rules answers:

> What happens mechanically?

> What can a player select?

> What bonuses or penalties exist?

> How does the system resolve it?

> What changes during character creation or advancement?

---

# 48. Magic / Lineage Separation

Lineages should not duplicate the mechanics of Elements or Variants.

For example:

```text
Magic System/Elements/Sub-Elements/Fire/Flame.md
```

owns the mechanics of Flame.

A future:

```text
Rules/Character/Lineages/Sericari/Embercoil.md
```

may explain:

- that Embercoil culture is associated with Flame
- which Flame traditions are culturally important
- what Embercoil characters can access
- any lineage-specific interaction

It should not copy the complete Flame rules.

---

# 49. Migration Status Vocabulary

Every migration item should use one of these statuses:

```text
Create
Consolidate
Rebuild
Reorganize
Preserve
Deprecate
Archive
Resolve
```

## Create

No authoritative file currently exists.

## Consolidate

Several existing sources need to become one authoritative file.

## Rebuild

The existing file contains useful material but its structure/mechanics are outdated.

## Reorganize

The content is fundamentally valid but belongs elsewhere.

## Preserve

The file is already structurally useful and should remain largely intact.

## Deprecate

The file should stop being used as an authoritative source.

## Archive

The file is historical and should be retained for reference only.

## Resolve

The underlying concept contains a contradiction or unresolved mechanic.

---

# 50. Migration Order Rule

Do **not** migrate lineages simply because their historical files are available.

The required dependency direction is:

```text
Repository Architecture
        ↓
Core Rules
        ↓
Character Rules
        ↓
Biology
        ↓
Paths
        ↓
Social Rules
        ↓
Magic Foundation
        ↓
Elements / Variants
        ↓
Base Lineages
        ↓
Silk-Lineages
        ↓
Conditions / Afflictions
        ↓
Examples
        ↓
Reference
        ↓
Legacy Cleanup
```

This prevents lineage files from becoming containers for unresolved system mechanics.

---

# 51. Final Migration Goal

The finished repository should have a clear ownership structure:

```text
Anymalis/
│
├── Lore/
│   ├── World/
│   ├── History/
│   ├── Cosmology/
│   ├── Lineages/
│   ├── Conditions/
│   └── Clans/
│
├── Rules/
│   ├── Core/
│   ├── Character/
│   ├── Biology/
│   ├── Paths/
│   ├── Social/
│   ├── Conditions/
│   └── Integration/
│
├── Magic System/
│   ├── Core/
│   ├── Construction/
│   ├── Elements/
│   ├── Meta-Glyphs/
│   ├── Outlines/
│   └── Inks/
│
├── Examples/
│   ├── Characters/
│   ├── Spells/
│   └── Lineages/
│
├── Reference/
│
├── Archive/
│   └── Legacy/
│
└── _system/
    ├── Canon.md
    ├── Architecture.md
    ├── Naming Conventions.md
    └── Migration.md
```

The central design principle is:

```text
ONE CONCEPT
      ↓
ONE AUTHORITATIVE OWNER
      ↓
OTHER FILES REFERENCE IT
```

The migration should preserve useful existing canon while removing duplicate ownership, resolving contradictions explicitly, and preventing historical mechanics from silently becoming current rules.