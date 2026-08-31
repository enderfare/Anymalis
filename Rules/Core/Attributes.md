# Attributes

Anymalis uses six core attributes.

| Attribute | Abbrev. | Represents |
|---|---|---|
| Might | MGT | Strength, force, physical power |
| Finesse | FIN | Agility, precision, reflexes |
| Endurance | END | Stamina, resilience, recovery |
| Intellect | INT | Knowledge, reasoning, technical thought |
| Insight | INS | Perception, intuition, pattern recognition |
| Presence | PRS | Willpower, influence, composure |

## Modifier

```text
Attribute Modifier = floor((Attribute - 10) / 2)
```

## Starting Generation

Default point-buy:

- All attributes begin at 8.
- Characters receive 72 points to distribute.
- Maximum starting value: 18.
- Increasing an attribute from 8 through 14 costs 1 point per increase.
- Increasing an attribute above 14 costs 2 points per increase.

### Point-Buy Cost Table

| Score | Total Cost |
|---:|---:|
| 8 | 0 |
| 9 | 1 |
| 10 | 2 |
| 11 | 3 |
| 12 | 4 |
| 13 | 5 |
| 14 | 6 |
| 15 | 8 |
| 16 | 10 |
| 17 | 12 |
| 18 | 14 |

A score can never exceed 18 during character creation unless a rule explicitly says otherwise.

### Example

A character with:

```text
18 / 16 / 14 / 12 / 10 / 10
```

spends:

```text
14 + 10 + 6 + 4 + 2 + 2 = 38 points
```

The remaining points may be distributed among the attributes, provided the final values remain within the starting-generation limits.

Attributes represent aptitude, not training.

A character with high FIN and low Marksmanship skill is naturally precise but inexperienced. A character with moderate FIN and Master Marksmanship is highly trained.
