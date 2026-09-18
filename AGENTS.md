# Western content pack

This folder is Part 2 of MCV and requires sibling `../mcv` (Part 1, Eastern + Base).
Keep all weapon bases, entities, autorun/shared code, settings and common systems in Part 1.
Part 2 contains weapon definitions and exclusive assets only.

Follow `../mcv/AGENTS.md`. Do not launch or run in-game verification without an explicit
user request. Preserve hand-tuned weapon fields and stage changes explicitly if asked to
commit. Source/compile files and all build tooling stay in `../mcv/work`; use
`../mcv/work/pack_paths.py` to resolve installed assets across both packs.
