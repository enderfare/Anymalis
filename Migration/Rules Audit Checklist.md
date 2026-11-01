# Rules Audit Checklist

Complete this audit before consolidating or authoring replacement files. Paths are relative to the original repository root. If a listed file is absent, record that fact rather than inventing a substitute.

## 1. Inventory and ownership

- [ ] List every file under `Rules/` and record its purpose.
- [ ] For each rule concept, identify one authoritative owner.
- [ ] Identify duplicate, partial, or conflicting definitions.
- [ ] Record inbound/outbound links and files that depend on each definition.
- [ ] Mark source files as preserve, merge, split, rename, archive, or remove only after review.

## 2. Mandatory overlap checks

| Concept | Exact source paths | Audit result / target owner |
|---|---|---|
| Traits | `Rules/Character/Traits.md` plus any other Rules file defining traits | — |
| Techniques | `Rules/Character/Techniques.md`; `Rules/Skills/Techniques.md` | — |
| Skills | `Rules/Character/Skills.md`; `Rules/Skills/Skills.md` | — |
| Character creation | `Rules/Character/Character Creation.md`; verify whether `Rules/Integration/Character-Creation.md` exists | — |
| Integration | All files under `Rules/Integration/` | — |
| Attributes and checks | All files under `Rules/` defining attributes, checks, saves, or resolution | — |
| Derived statistics/resources | All files defining formulas, pools, recovery, or thresholds | — |
| Biology | Files defining ATS, HTS, Q%, and biological traits | — |
| Paths | Files defining Paths, Path Skills, Path Abilities, and eligibility | — |
| Advancement | Files defining practice, instruction, experience, mastery, and transformation | — |
| Social systems | Files defining Renown, Reputation, Tags, Rumors, and social integration | — |

## 3. Formula audit

For every formula, record: name, canonical definition path, variables, units/range, minimum/maximum, rounding, edge cases, recovery/update timing, and dependent files.

- [ ] No undefined variable or statistic is used.
- [ ] No formula silently produces values outside its intended range.
- [ ] Terms such as `Training`, `Skill Mastery Bonus`, `Affinity Bonus`, `ATS`, `HTS`, `Q%`, `RST`, `SAN`, and Glyph Fatigue are defined consistently.
- [ ] Derived values have a single authoritative formula.
- [ ] Examples match the current formula.

## 4. Legacy terminology audit

Search for these terms and record whether each is intentionally retained, mapped to an Anymalis term, or removed: `Proficiency Bonus`, `spell level`, `WIS`, `DEX`, `saving throw`, `AC`, `advantage`, `disadvantage`, `short rest`, `long rest`, `HP`.

## 5. Exit gate

Do not mark the Rules foundation complete until:

- [ ] Every source file has a disposition.
- [ ] Every concept has one authoritative owner.
- [ ] Conflicts are resolved or entered in `Decision Log.md` with a safe deferral boundary.
- [ ] The migration matrix reflects the chosen merge/split/rename behavior.
- [ ] Target files are checked for broken links and duplicated definitions.
