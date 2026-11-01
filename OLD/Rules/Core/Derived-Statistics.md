# Derived Statistics

These statistics preserve the existing Anymalis resource model.

## Resonance Capacity (RES)

```text
RES = (Insight × 2) + Presence + Training
```

**Training is optional.**

If a character has no applicable Training bonus, Training is treated as `0`.

Training represents an existing trained capability or other rule that explicitly grants a Training value. It is not automatically gained merely from spending time in the world.

---

## Sanity (SAN)

SAN exists for every character.

```text
SAN = (Insight × 5) + Intellect + Presence
```

SAN represents mental and psychological stability.

SAN is independent from Glyph Fatigue.

---

## Animen (ANI)

Animen is the personal magical resource used to directly manipulate Elemental Resonance.

```text
ANI = (Insight × 3) + (Presence × 2) + Element Tier Bonus
```

Tier bonuses:

| Tier | Bonus |
|---|---:|
| Mythic | +30 |
| Primordial | +25 |
| Fundamental | +20 |
| Physical | +15 |
| Terrestrial | +10 |

Animen may allow a capable character to construct or manifest spells without conventional conductive Ink.

---

## Glyphic Ink Capacity (INK)

```text
INK = 1 + floor(Intellect / 4) + Affinity Bonus
```

INK measures how much prepared conductive Ink the character can effectively maintain or carry as part of their normal magical resources.

---

## Energy (ENR)

```text
ENR = (Endurance × 4) + (Might × 2)
```

## Strain (STRN)

```text
STRN = (Endurance × 2) + Presence
```

---

## Combat Derivatives

```text
HP = (Endurance × 3) + (Adventuring Tier × 2)

Defense = 10 + Finesse Modifier + Armor + Shield

Initiative = d20 + Finesse Modifier + Insight Modifier

Carry Capacity = Might × 15 lbs

Speed = 30 ft + (Finesse Modifier × 5)
```

---

## Magic Derivatives

```text
Glyph Save DC = 8 + INT Modifier + INS Modifier + Proficiency

Glyph Attack = INT or INS Modifier + Proficiency

Magical Resistance = Insight Score + Wards + RES Modifier

Resonance Resistance = Presence Modifier + (RES ÷ 2)
```

These formulas are isolated here so the rest of the character system does not need to duplicate them.
