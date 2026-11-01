# Lineages

Lineages represent a character's inherited biological identity and the cultural traditions associated with it.

A Lineage describes **what a character is**, but it does not determine their Path, Element, Variant, or personal history.

A Lineage should provide a foundation for a character without defining the entire character.

---

# Lineage Structure

A standard Lineage provides:

```text
1 Skill Training
1 Lineage Trait
1 Lineage Technique
```

A strongly specialized Lineage may additionally provide:

```text
1 Lineage Specialization
```

These features should reinforce the identity of the Lineage without replacing the universal character systems.

---

# Skill Training

A Lineage grants one Skill Training.

The chosen skill should represent a skill commonly developed through the Lineage's biology, culture, environment, or traditions.

A Lineage should not grant unrestricted access to multiple Skills unless a specific rule states otherwise.

Lineage Training cannot normally raise a character's starting Skill above **Skilled**.

---

# Lineage Traits

A Lineage grants one Lineage Trait.

A Lineage Trait represents a persistent biological, cultural, sensory, or social characteristic shared by members of the Lineage.

Examples include:

```text
Natural Climber
Acute Hearing
Resonance Sensitive
Natural Armor
Exceptional Memory
Night Adaptation
Natural Silk Production
```

A Lineage Trait should have a concrete mechanical or narrative effect.

Lineage Traits should not be used as generic numerical bonuses when a more specific rule can express the same identity.

---

# Lineage Techniques

A Lineage grants one Lineage Technique.

A Lineage Technique represents something members of the Lineage can actively do because of their biology, cultural training, or unique relationship with the world.

A Lineage Technique may interact with:

* Skills
* Resonance
* Movement
* Combat
* Craft
* Social interaction
* Survival
* Other character systems

A Lineage Technique must follow the normal rules of the system it interacts with.

A Lineage Technique should not introduce an entirely separate subsystem unless the Lineage itself requires one.

---

# Lineage Specializations

Some Lineages contain particularly specialized cultural or biological traditions.

Such a Lineage may provide one optional Lineage Specialization.

A Specialization represents a narrower identity within the broader Lineage.

For example:

```text
Sericari
    ↓
Silk-Lineage
    ↓
Individual
```

A Specialization should not replace the character's individual Resonant Affinity or Variant unless a specific rule establishes that relationship.

---

# Lineage and Resonance

Lineage and Elemental Affinity are separate concepts.

A Lineage may have cultural or biological associations with particular Elements, but this does not automatically determine a character's Elemental Affinity.

A naturally magical character normally expresses their affinity through their **Resonant Scar**.

The relationship is therefore:

```text
Lineage
    │
    ├── Biology
    ├── Culture
    ├── Skill Training
    ├── Lineage Trait
    └── Lineage Technique
            │
            ↓
       Individual
            │
            └── Resonant Scar
                    │
                    ├── Element
                    └── Variant
```

This allows members of the same Lineage to possess different magical identities.

---

# Lineage and Paths

Lineage does not determine Path.

A member of any Lineage may potentially become a:

```text
Scribe
Channeler
Artificer
Null
```

A Lineage may have cultural traditions that make certain Paths common, but those traditions do not restrict individual character choice unless a specific rule states otherwise.

---

# Lineage and Background

Lineage and Background describe different aspects of a character.

```text
Lineage
= inherited identity

Background
= formative experience and upbringing
```

Two characters of the same Lineage may have completely different Backgrounds.

Likewise, members of different Lineages may share the same Background.

---

# Lineage and Traits

Lineage Traits are a source of Traits, but not every Trait a character possesses must come from their Lineage.

Traits may come from:

* Lineages
* Backgrounds
* Paths
* Training
* Transformations
* Major story events

Lineage Traits should describe something meaningfully associated with the Lineage.

---

# Biological Statistics

Some Anymalis rules use biological measurements that are separate from the normal player-facing Lineage feature package.

These include:

### Animal Trait Score

ATS represents the degree to which a character expresses animal-derived biological traits.

ATS is measured on a scale from 0–10.

### Hybrid Trait Score

HTS represents the degree of hybrid biological expression.

HTS is measured on a scale from 0–10.

### Quimera Percentage

The current biological model uses:

```text
Q% = (ATS × 5) + (HTS × 3) + (RES ÷ 10)
```

Q% represents the calculated likelihood of unstable offspring under the current biological model.

The calculation and interpretation of Q% should be treated as a **biological rule**, not as a standard benefit granted by choosing a Lineage.

The biological system should be maintained separately from the player-facing Lineage feature package.

---

# Starting Limits

Lineage features should not bypass normal character creation limits.

Unless a specific rule states otherwise:

* Lineage Skill Training cannot raise a starting Skill above Skilled.
* Lineage Traits do not provide unrestricted numerical bonuses.
* Lineage Techniques follow the normal rules of the system they interact with.
* Lineage does not automatically determine Elemental Affinity.
* Lineage does not automatically determine Path.
* Lineage does not replace Background.

---

# Design Principle

A Lineage should answer:

> **What makes these people distinct?**

It should not answer:

> **What is the entire character capable of?**

The universal character systems provide the latter.

A well-designed Lineage should therefore provide a small number of meaningful features that express its identity while leaving room for individual characters to differ.

---

# Lineage File Structure

Individual Lineage rules should use the following structure:

```text
# [Lineage]

## Identity

## Skill Training

## Lineage Trait

## Lineage Technique

## Lineage Specialization

## Biological Notes

## Resonance Relationship

## Character Considerations
```

Not every section is required for every Lineage.

A section should only exist when the Lineage actually needs it.
