# Migration Plan

## Purpose and scope

This folder is the migration control pack. It can be used independently of the source repository. The file paths in the inventory and matrix are **relative to the original repository root** unless explicitly prefixed with `New/` or `Old/Repository Snapshot/` in the matrix.

The migration is a controlled consolidation, not a blind file move. Preserve source material until a target has been written, checked, linked, and approved.

## Start here

1. Read [`Canon.md`](Canon.md) before treating any legacy content as canon.
2. Read [`Decision Log.md`](Decision%20Log.md) and resolve or explicitly defer open contradictions.
3. Use [`Migration Matrix.md`](Migration%20Matrix.md) as the human-readable source-to-target map. Use [`Migration Matrix.csv`](Migration%20Matrix.csv) for sorting, filtering, and tracking.
4. Use [`Old Files to Migrate.md`](Old%20Files%20to%20Migrate.md) to verify the source inventory.
5. Use [`New Files to Create.md`](New%20Files%20to%20Create.md) as the target-path checklist. A listed path is a plan, not proof that a file has been created.
6. Complete the Rules audit below before writing replacement Rules files.
7. Migrate by phase, validate each phase, and only then proceed.

## Phase order

### Phase 0 — Audit and architecture
- [ ] Confirm the source inventory against the current repository.
- [ ] Confirm canon hierarchy and historical-source policy.
- [ ] Establish the architecture, naming conventions, and migration status conventions.
- [ ] Correct target paths in the matrix before moving or rewriting files.

### Phase 1 — Rules foundation
- [ ] Audit the full `Rules/` tree for duplicate ownership and conflicting definitions.
- [ ] Consolidate attributes, checks/core resolution, derived statistics, resources, and terminology.
- [ ] Keep formulas and named statistics defined in one authoritative location.

### Phase 2 — Character rules
- [ ] Consolidate skills, specializations, techniques, traits, backgrounds, and advancement.
- [ ] Finalize character creation and integration after the underlying rules stabilize.
- [ ] Reconcile Training, Skill Mastery Bonus, and any legacy proficiency terminology.

### Phase 3 — Biology and Paths
- [ ] Resolve ATS, HTS, Quimera Percentage, and biological-trait formulas.
- [ ] Consolidate the four Paths, Path Skills, Path Abilities, and integration rules.
- [ ] Consolidate Renown, Reputation, Tags, Rumors, and social integration.

### Phase 4 — Magic foundation
- [ ] Define Resonance, Glyphs, Resonant Scar, Resonance Stability (RST), and Glyph Fatigue.
- [ ] Finalize spell construction, Foundation, Borders, other outlines, conductors, inks, and surfaces.
- [ ] Define Meta-Glyph ownership and rules without treating Prima/Nihil as ordinary Elements.
- [ ] Resolve Element/Variant identity versus Transformation behavior.

### Phase 5 — Elements and Variants
- [ ] Normalize the 11 Element files and their Variant ownership.
- [ ] Preserve the rule that each Variant belongs to exactly one Element.
- [ ] Check all Variant counts and links; do not recreate existing Variant rules inside lineage documents.

### Phase 6 — Lineages and conditions
- [ ] Migrate each base lineage with a Lore file and a corresponding Rules file.
- [ ] Migrate every Sericari Silk-Lineage as a Lore/Rules pair.
- [ ] Silk-Lineage documents describe culture, biology, and traditions; Variant files own Variant mechanics.
- [ ] Resolve Conditions/Afflictions and the current Illuminated structure.

### Phase 7 — Examples, links, and release checks
- [ ] Update examples only after the rules they demonstrate are stable.
- [ ] Check every internal link and every source-to-target mapping.
- [ ] Search for duplicate definitions, stale names, contradictory formulas, and D&D-specific terms.
- [ ] Mark each migration row with its actual status and preserve superseded source files in the legacy archive.

## Rules audit: required overlap checks

Before authoring replacement files, inspect these exact source paths and their linked references:

- `Rules/Character/Traits.md` and every other file defining traits.
- `Rules/Character/Techniques.md` and `Rules/Skills/Techniques.md`.
- `Rules/Character/Skills.md` and `Rules/Skills/Skills.md`.
- `Rules/Character/Character Creation.md` and, **if present in the current source**, `Rules/Integration/Character-Creation.md`.
- All files under `Rules/Integration/` that define or repeat character creation, advancement, paths, or social mechanics.
- All files under `Rules/` that define attributes, checks, resources, formulas, Training, Skill Mastery, ATS, HTS, or Quimera Percentage.

Do not assume a path exists because it appears in a previous plan. Verify it in the actual source tree.

## Non-negotiable migration rules

- Inspect every mapped source before creating or replacing its target.
- Never create two authoritative files for one concept. Merge, split, rename, or cross-reference deliberately.
- Keep Element and Variant mechanics in the Magic System; lineages reference these rules rather than duplicating them.
- Every new `Rules/Character/Lineages/<Lineage>.md` requires a corresponding `Lore/Lineages/<Lineage>.md`.
- Every Sericari Silk-Lineage needs both `Lore/Lineages/Sericari/<Silk-Lineage>.md` and `Rules/Character/Lineages/Sericari/<Silk-Lineage>.md`.
- Record unresolved contradictions in `Decision Log.md`; do not silently choose one interpretation.
- Keep the original source snapshot unchanged until the migration is validated.
- Mark a file complete only after content review, formula/link checks, and ownership checks—not merely after copying it.

## Completion criteria

A phase is complete only when all applicable source files are accounted for, targets are authored and reviewed, links work, duplicate ownership is resolved, open decisions are recorded, and the matrix status reflects reality.
