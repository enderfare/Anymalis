# Spell Construction Examples

This document demonstrates how the rules of Anymalis interact in practice.

These examples are intended to clarify the rules and terminology.

---

## Example 1 — Simple Elemental Construction

```text
Element:
Fire

Variant:
Flame

Border:
Foundation

Conductor:
Ember Ash

Surface:
Stone
```

**Result:** A stable Flame Glyph with a stronger conceptual Fire presence.

The Foundation does not create Fire. Fire was already established by the Core Glyph.

---

## Example 2 — Multi-Element Spell

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

**Result:** A precise stream of extremely hot air.

This spell contains two Elements.

It does not create a new Fire/Wind Element.

---

## Example 3 — Same Variant Name, Different Elements

```text
Water → Flow
Time → Flow
```

The two `Flow` Variants are not the same Variant.

Each belongs to its own Element.

Water Flow concerns the movement of water.

Time Flow concerns progression through time.

---

## Example 4 — Animen Casting

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

**Result:** The caster directly manifests the Flame construction without conventional Ink.

---

## Example 5 — Sericari Casting

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

**Result:** The Sericari constructs the Glyph through their own Resonant Threads.

---

## Example 6 — Artificer With Affinity

```text
Path:
Artificer

Affinity:
Fire

Device:
Ember Gauntlet

Construction:
Fire → Ember

Borders:
Trigger
Containment
Amplification
```

The Artificer uses their Fire affinity to work with the relevant Element, but their Path is defined by creating the device.

---

## Example 7 — Artificer Without Affinity

```text
Path:
Artificer

Affinity:
None

Device:
Resonance Cartridge

Construction:
Fire → Flame

Source:
Stored Fire Resonance
```

The Artificer does not need a natural Fire affinity to create or operate a device using prepared Fire Resonance.

---

## Example 8 — Surface Without Special Effect

```text
Surface:
Stone
```

Stone simply provides a stable medium.

No additional Surface effect is assumed unless that specific Surface has been designated as Resonant.

---

## Example 9 — Resonant Surface

```text
Surface:
[Named Resonant Surface]

Surface Property:
Provides the explicitly listed additional effect.
```

Only the designated Resonant Surface property applies.

Do not assume every object or material has a special Surface effect.

---

## Example 10 — Death

```text
Element:
Death

Variant:
End
```

**Result:** The target's existing process or manifestation is brought to an end.

A Flame may cease to burn.

---

## Example 11 — Nihil

```text
Element:
Nihil
```

**Result:** The construction attacks existence, definition, connection, or conceptual continuity rather than merely ending an existing process.

Death and Nihil can therefore produce superficially similar outcomes while operating on different principles.

---

## Example 12 — Prima vs Nihil

```text
Prima
vs.
Nihil
```

Neither automatically wins.

Equivalent opposing constructions enter a contest.

The result depends on the actual constructions, circumstances, and resolution rules.

---

# Invalid Constructions

## Invalid Variant Assignment

```text
Fire → Mist
```

Mist is a Water Variant.

---

## Invalid Hybrid Element

```text
Fire/Water → Steam
```

Steam can be a result of combining appropriate Fire and Water Variants, but it should not automatically become a new Element or Variant.

---

## Invalid Border Usage

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

## Invalid Generic Variant

```text
Fire → Projectile
```

Projectile describes a form of spell delivery, not a fundamental expression of Fire.

Use appropriate Fire Variants and Borders to create a projectile instead.
