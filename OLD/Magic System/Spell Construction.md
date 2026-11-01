# Spell Construction

A Spell is a complete magical construction created by combining Elements, Variants, Borders, conduction methods, and, when applicable, a Surface.

## Construction Model

```text
Spell
├── Element(s)
│   └── Variant(s)
├── Border(s)
├── Foundation
├── Conduction
│   ├── Ink
│   ├── Animen
│   └── Resonant Threads
└── Surface
```

Not every spell must use every physical component.

---

## 1. Select Elements

A Spell may use one or more Elements.

```text
Fire
```

or:

```text
Fire
+
Wind
```

or:

```text
Fire
+
Wind
+
Water
```

There is no automatic creation of a new hybrid Element.

---

## 2. Select Variants

Every Variant must belong to one of the selected Elements.

Valid:

```text
Fire → Heat
Wind → Flow
```

Invalid:

```text
Fire → Mist
```

because Mist belongs to Water.

---

## 3. Add Borders

Borders define how the selected Elemental Resonance behaves.

Example:

```text
Fire → Heat
Wind → Flow

Borders:
- Flow
- Precision
```

The Elements describe what is being manipulated.

The Borders describe how the construction behaves.

---

## 4. Foundation

Foundation may be added when a Glyph needs greater conceptual importance within the construction.

```text
Fire → Flame
+
Foundation
```

Foundation strengthens the existing Fire Glyph.

It does not create Fire and cannot change the Element.

---

## 5. Choose a Conduction Method

### Ink

The traditional method.

```text
Conductor: Ember Ash
```

### Animen

A capable user may construct or manifest the spell directly through their personal Animen.

```text
Conductor: Animen
```

### Resonant Threads

Sericari can use their Resonant Threads.

```text
Conductor: Resonant Threads
```

---

## 6. Choose a Surface

A Surface is the physical medium used by the construction.

Standard Surfaces include:

- Stone
- Skin
- Paper
- Cloth
- Metal
- Living Wood

A Surface only adds a special effect if it is explicitly designated as a Resonant Surface.

---

# Examples

## Simple Spell — Ember Mark

```text
Element:
Fire → Ember

Borders:
Foundation

Conductor:
Ember Ash

Surface:
Stone
```

**Effect:** A persistent ember Glyph that maintains a stronger-than-normal Fire presence.

---

## Multi-Element Spell — Thermal Current

```text
Elements:
Fire → Heat
Wind → Flow

Borders:
Flow
Precision

Conductor:
Ember Ash

Surface:
Metal
```

**Effect:** A controlled stream of extremely hot air.

---

## Multi-Element Spell — Temporal Tide

```text
Elements:
Water → Flow
Time → Flow

Borders:
Flow
Duration

Conductor:
Silverthread

Surface:
Cloth
```

**Effect:** A moving body of water whose temporal progression can be accelerated or slowed.

---

## Animen Spell — Flame Lance

```text
Element:
Fire → Flame

Borders:
Precision
Transformation

Conductor:
Animen

Surface:
None
```

**Effect:** A directly manifested lance of Fire without conventional Ink.

---

## Sericari Spell — Threaded Flame

```text
Element:
Fire → Flame

Borders:
Precision
Duration

Conductor:
Resonant Threads

Surface:
None
```

**Effect:** A Flame construction woven directly through the Sericari's Resonant Threads.

---

## Three-Element Spell — Stormheart

```text
Elements:
Fire → Heat
Wind → Flow
Water → Rain

Borders:
Flow
Amplification
Duration

Conductor:
Silverthread

Surface:
Metal
```

**Effect:** A storm of heated rain driven by controlled air currents.

---

# Invalid Examples

## Invalid Variant

```text
Fire → Mist
```

Mist belongs to Water.

Correct:

```text
Fire → Heat
Water → Mist
```

if the spell requires both.

---

## Invalid Hybrid Element

```text
Fire/Water → Steam
```

Do not create a hybrid Element solely because two Elements interact.

Instead:

```text
Fire → Heat
Water → Mist
```

and construct a spell that produces steam as its result.

---

## Invalid Foundation

```text
Foundation → Fire
```

Foundation cannot establish an Element.

Correct:

```text
Fire → Flame
+
Foundation
```

---

# Design Principle

The construction process can be summarized as:

```text
WHAT?
Element

WHICH EXPRESSION?
Variant

HOW?
Borders

HOW IMPORTANT?
Foundation

HOW IS IT CONDUCTED?
Ink / Animen / Resonant Threads

WHERE?
Surface

WHAT DOES THE COMPLETE CONSTRUCTION PRODUCE?
Spell Effect
```
