# Military Conflict: Vietnam — Part 2: Western

**Requires Military Conflict: Vietnam — Part 1: Eastern & Base.**

This is a content-only expansion: 157 Western weapon/equipment definitions and their
exclusive models, materials and sounds. All shared weapon bases, entities, settings,
effects, shaders and other common code live in the sibling `mcv` (Part 1) addon.
Install both packs to get the complete set. Part 1 works on its own.

US, Commonwealth and Western European weapons are here, including the German weapons.
Country-based random selectors can still place a weapon in several service/nation pools;
each weapon class is installed in just one pack.

Workshop publishing: add **Part 1** in this item's **Add/Remove Required Items** list.
`addon.json` does not establish a Steam Workshop dependency. Do not mark Part 1 as requiring
Part 2. The release descriptor in `../mcv/work/pack_split/workshop.json` records that direction;
the Workshop item IDs must be filled in when publishing. No Workshop upload is performed
by the build scripts.

`icon.jpg` is the 512×512 baseline JPEG for Workshop. The 2048×2048 version is kept
under the base addon's `work/artwork/part2-western/addon-icon-hd.png`.
Both say **Part 2 - Western** and use only this pack's original-game gun HUD silhouettes.

Source/compile files remain in `../mcv/work`, including all three custom guns. Their compile
scripts resolve installed paths across both packs. See `../mcv/work/pack_split/README.md`
for the manifest, verified GMA outputs and rebuild instructions.

Fully restart GMod after splitting or installing these folders so the new addon is mounted.
