# Character Creation

Character creation combines the modular systems of Anymalis.

Characters are built from several independent components:

```text
Attributes
Skills
Specializations
Techniques
Background
Lineage
Path
Traits
Reputation
Derived Statistics
```

These systems interact, but no single component determines the complete character.

---

## Step 1 — Attributes

Generate the six Attributes using the standard point-buy rules.

```text
MGT — Might
FIN — Finesse
END — Endurance
INT — Intellect
INS — Insight
PRS — Presence
```

Attributes represent the character's broad underlying capabilities.

Use the current Attribute rules for point-buy costs, minimums, maximums, and starting values.

---

## Step 2 — Universal Skills

Gain:

```text
6 Skill Trainings
```

Each Skill Training raises one Skill:

```text
Untrained → Trained
```

These Trainings represent the character's general development and may be distributed among the available Skills.

Universal Skill Trainings are independent of Skill Trainings gained from Background, Path, or Lineage.

---

## Step 3 — Background

Choose a Background.

Gain:

```text
2 Skill Trainings
1 Specialization
1 Trait
```

Background represents the character's individual history and the experiences that shaped them.

Background benefits should reflect that history.

A Background should not determine the character's Lineage or Path.

---

## Step 4 — Path

Choose one of the Four Paths:

```text
Scribe
Channeler
Artificer
Null
```

Gain:

```text
2 Path Skill Trainings
1 Path Ability
```

### Scribe

Specializes in Glyph construction, magical design, preparation, versatility, and control.

### Channeler

Specializes in direct Resonance manipulation, physical enhancement, speed, and close combat.

### Artificer

Specializes in Resonance engineering, devices, tools, materials, and preparation.

### Null

Specializes in anti-Resonance interaction, disruption, cancellation, and magical suppression.

Path determines a character's primary magical discipline.

Path does not determine:

* Lineage
* Element
* Variant
* Background
* Personality
* Personal beliefs

---

## Step 5 — Lineage

Choose a Lineage.

Gain:

```text
1 Skill Training
1 Lineage Trait
1 Lineage Technique
```

Lineage represents inherited biological identity and cultural traditions.

The Lineage Skill Training should reflect a meaningful capability associated with that Lineage.

The Lineage Trait represents a persistent characteristic of the Lineage.

The Lineage Technique represents a specific ability or method associated with the Lineage.

Lineage does not determine:

* Path
* Element
* Variant
* Resonant Scar
* Background
* Personality

Elemental Affinity, when applicable, is determined through the character's Resonant Scar rather than automatically through Lineage.

---

## Step 6 — Techniques

Start with:

```text
2 Basic Techniques
```

Additional Techniques may come from:

* Background
* Lineage
* Path
* Instruction
* Advancement
* Other explicitly defined sources

A Technique represents a specific deliberate application of a character's capabilities.

Techniques should not duplicate the function of Skills or Traits.

### Basic Techniques

Basic Techniques are broadly available techniques that do not require specialized Lineage, Path, or other prerequisites.

The available Basic Techniques are defined in the appropriate Technique rules.

---

## Starting Skill Cap

No Skill may begin above:

```text
Skilled
```

unless a specific campaign rule explicitly overrides this.

This cap applies to the character's starting Skill state after all starting Skill Trainings have been applied.

If multiple character-creation sources grant Training in the same Skill, apply the existing duplicate-training rules rather than automatically exceeding the cap.

---

## Step 7 — Reputation

New characters normally begin with:

```text
Renown: 0
Public Reputation: 0
```

Background, Lineage, campaign setting, or prior history may establish additional Reputation Tracks or Tags.

A character with a significant established history may begin with a specific Reputation Tag if the GM approves it.

Reputation does not determine a character's actual Skill level.

Use the established distinction:

```text
Skill = what you can do
Renown = how many people know you
Reputation = what they think
Tags = what they associate with you
Rumors = what they believe
```

---

## Step 8 — Derived Statistics

Calculate the character's derived statistics using `Derived-Statistics.md`.

These include:

```text
RES
SAN
ENR
ANI
INK
STRN
HP
Defense
Initiative
```

and any other derived values defined by the current rules.

Derived Statistics should be calculated only after the character's required starting values have been established.

Do not create alternative formulas inside Character Creation.

---

# Final Character Architecture

```text
ATTRIBUTES
   ↓
SKILLS
   ↓
SPECIALIZATIONS
   ↓
TECHNIQUES

BACKGROUND ──┐
LINEAGE ─────┼──→ TRAITS
PATH ────────┘

PATH ──→ PATH ABILITIES

EVENTS ──→ RENOWN
       └──→ REPUTATION
             ├──→ TAGS
             └──→ RUMORS

All systems interact with
the existing Glyphic Resonance rules.
```

---

# Character Creation Summary

A starting character receives:

| Source             | Starting Benefits                                      |
| ------------------ | ------------------------------------------------------ |
| Attributes         | Six Attributes generated by point-buy                  |
| Universal Skills   | 6 Skill Trainings                                      |
| Background         | 2 Skill Trainings, 1 Specialization, 1 Trait           |
| Path               | 2 Path Skill Trainings, 1 Path Ability                 |
| Lineage            | 1 Skill Training, 1 Lineage Trait, 1 Lineage Technique |
| Techniques         | 2 Basic Techniques                                     |
| Reputation         | Renown 0, Public Reputation 0                          |
| Derived Statistics | Calculated from current rules                          |

Starting Skills cannot normally exceed **Skilled**.

---

# Character Creation Principle

Character creation should produce an individual assembled from interacting systems rather than a single predefined package.

```text
Lineage
    ≠
Path
    ≠
Background
    ≠
Resonant Affinity
```

Each answers a different question about the character.

The resulting character is defined by the combination of their inherited identity, personal history, learned capabilities, chosen Path, Traits, Techniques, Resonance, and experiences.

All character-creation rules must remain compatible with the broader Anymalis rules and Glyphic Resonance systems.
