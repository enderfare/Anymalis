# Anymalis Migration Pack

This folder contains **only migration planning and control documents**. It does not contain the source repository or the planned destination files.

## Recommended reading order

1. **[Migration Plan](Migration%20Plan.md)** — the execution sequence and non-negotiable rules.
2. **[Canon](Canon.md)** — canon precedence and how to treat current versus historical sources.
3. **[Decision Log](Decision%20Log.md)** — contradictions that need explicit decisions.
4. **[Rules Audit Checklist](Rules%20Audit%20Checklist.md)** — mandatory duplicate/ownership/formula audit before writing replacement Rules files.
5. **[Migration Matrix](Migration%20Matrix.md)** — human-readable mapping from each source file to its planned destination/disposition.
6. **[Migration Matrix CSV](Migration%20Matrix.csv)** — spreadsheet-friendly version of the mapping.
7. **[Old Files to Migrate](Old%20Files%20to%20Migrate.md)** — source inventory (187 files in the reviewed snapshot).
8. **[New Files to Create](New%20Files%20to%20Create.md)** — planned destination paths (172 paths in the current plan; not all are necessarily new authored content).
9. **[Status Tracker](Status%20Tracker.md)** — phase-level readiness tracker.

## Important interpretation rules

- All source paths are relative to the original repository root unless the matrix explicitly prefixes them with `Old/Repository Snapshot/`.
- Target paths are plans. A target path does not mean the file exists or is approved.
- Several source files may intentionally map to one target. Those collisions require a reviewed merge/split/reference decision; do not overwrite one source with another.
- `Lineages (Simple) Outdated/` is historical reference material, not current canon by default.
- The current migration strategy prioritizes consolidating the non-lineage Rules and magic foundations **before** migrating lineage files.
- Every lineage Rules file must have a matching Lore file. Sericari Silk-Lineages require paired Lore and Rules documents.

## Known review warning

The matrix is a working proposal and must be audited before execution. In particular, check duplicate target paths, target folder naming, Element/Variant ownership, and whether every proposed target is needed. The Rules audit is intentionally a gate before authoring replacements.
