# Migration Decision Log

Use this log for decisions that affect canon, rules behavior, file ownership, or migration structure. Do not delete resolved decisions; retain the rationale so future edits do not reopen the same question accidentally.

## Status definitions

- **Open** — needs a decision before the affected rules/lore can be finalized.
- **Proposed** — a candidate answer exists but is not canon until explicitly approved.
- **Resolved** — decision has been approved and applied to all affected files.
- **Deferred** — intentionally postponed; record what work may safely proceed meanwhile.

When resolving an item, fill in the decision, rationale, date/version if tracked, and the target files that were updated.

| ID | Topic | Source paths to inspect | Required decision | Status | Decision / rationale | Targets updated |
|---|---|---|---|---|---|---|
| D-001 | Rimekin / Frost Variant | `Lore/Clans/Water/Rimekin.md`; `Magic System/Elements/Sub-Elements/Water/` | Decide whether Frost is a distinct Variant, a cultural term, or a manifestation of Ice/Temperature. Check the current Water Variant list before deciding. | Open | — | — |
| D-002 | Foundation vs Core Glyph | `Magic System/Core Principles.md`; `Magic System/Outlines/Core.md`; `Magic System/Outlines/Foundation.md` if present | Clarify which construction component establishes Element/Variant and what Foundation changes. | Open | — | — |
| D-003 | Transformation boundaries | `Magic System/Core Principles.md`; `Magic System/Outlines/Transformation.md` | Separate transformation of manifestation/behavior from changing the spell's Element or Variant identity. | Open | — | — |
| D-004 | Resonance Stability (RST) | Relevant files under `Magic System/` and `Rules/` | Define what RST measures, its formula or value source, tests, failure states, and recovery. | Open | — | — |
| D-005 | Glyph Fatigue | Relevant files under `Magic System/` and `Rules/` | Define generation, thresholds, effects, and recovery; keep it distinct from SAN and RST. | Open | — | — |
| D-006 | Training / Skill Mastery terminology | Relevant files under `Rules/` and `Magic System/` | Standardize terms and formulas; identify whether “Training” is a statistic, modifier, or descriptive label. | Open | — | — |
| D-007 | Quimera Percentage | Relevant files under `Rules/` defining ATS, HTS, and Q% | Resolve whether the formula can exceed 100 and define caps/normalization if appropriate. | Open | — | — |
| D-008 | Elemental Ink affinity bonus | Element files, `Magic System/Inks/`, and relevant `Rules/` formulas | Define how an Element's ink bonus maps to the character's ink formula; ensure one source of truth. | Open | — | — |
| D-009 | Duplicate Rules ownership | `Rules/Character/Traits.md`; `Rules/Character/Techniques.md`; `Rules/Skills/Techniques.md`; `Rules/Character/Skills.md`; `Rules/Skills/Skills.md`; relevant `Rules/Integration/` files | Choose one authoritative owner per concept and document any deliberate split. | Open | — | — |
| D-010 | Legacy D&D terminology | All files under `Rules/` and `Magic System/` | Identify and replace or explicitly retain terms such as Proficiency Bonus, spell level, ability saves, AC, advantage/disadvantage, short/long rest, and HP. | Open | — | — |
| D-011 | Element and Variant counts | Element index and all Element/Variant files | Verify the 11 Elements, their hierarchy, and expected Variant counts against the current canon. | Open | — | — |
| D-012 | Illuminated / Luminaris | `Lore/Lineages/Afflictions/Illuminated.md`; `Lineages (Simple) Outdated/Afflictions/Luminaris.md`; related rules | Confirm condition/affliction classification and ensure the historical lineage file is not treated as current mechanics. | Open | — | — |
| D-013 | Migration target collisions | `Migration Matrix.md` and `Migration Matrix.csv` | Review every case where multiple source files map to one target; specify merge/split/reference behavior before migration. | Open | — | — |
