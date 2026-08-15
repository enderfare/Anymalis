# Character Creation

Character creation combines the modular systems.

## Step 1 — Attributes

Generate six attributes using the standard point-buy.

```text
MGT
FIN
END
INT
INS
PRS
```

## Step 2 — Universal Skills

Gain:

```text
6 Skill Trainings
```

Each raises one Skill:

```text
Untrained → Trained
```

## Step 3 — Background

Gain:

```text
2 Skill Trainings
1 Specialization
1 Trait
```

## Step 4 — Path

Choose:

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

## Step 5 — Lineage

Gain:

```text
1 Skill Training
1 Lineage Trait
1 Lineage Technique
```

## Step 6 — Techniques

Start with:

```text
2 Basic Techniques
```

Additional techniques may come from Background, Lineage, Path, or advancement.

## Starting Skill Cap

No Skill may begin above:

```text
Skilled
```

unless a specific campaign rule explicitly overrides this.

## Step 7 — Reputation

New characters normally begin with:

```text
Renown: 0
Public Reputation: 0
```

Background, Lineage, campaign setting, or prior history may establish additional Reputation Tracks or Tags.

A character with a significant established history may begin with a specific Reputation Tag if the GM approves it.

## Step 8 — Derived Statistics

Calculate RES, SAN, ENR, ANI, INK, STRN, HP, Defense, Initiative, and other derived values using `Derived-Statistics.md`.

## Final Character Architecture

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
