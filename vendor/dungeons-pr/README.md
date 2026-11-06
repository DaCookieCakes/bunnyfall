# Dungeons PR

A quick demo of dungeon overhauls.

By Cookie. Made with the Bunnyfall Dungeon Editor, which writes everything in this folder: edit the project, not these files.

- `dungeon-editor.mod.json` - the mod's title, author and id range. Bunnyfall gives every folder with one a switch of its own (Settings > Gameplay > Dungeons; `src/systems/editorMods.js`).
- `WorldDataPatches/*.json` - dungeon blocks as changes over classic ones, rebuilt from the player's own BLOCKS.BSA. No Daggerfall data is shipped.
- `WorldData/*.json` - blocks built from nothing, and the mod's own places (`locationnew-bunnyfall-*`).
- `Models/<id>.json` - models from the editor's model editor (Bunnyfall only; Daggerfall Unity cannot load them).

Offline the mod also needs Replace Game Artwork (Asset Injection), like every world-data mod; online the room owns its switch.
