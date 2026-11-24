# Roboheckers — ParkourMaster007: The Awakening

A self-contained browser prototype for a 2D side-scrolling parkour, combat and RPG game starring Mike (ParkourMaster007), a sentient humanoid robot.

## Run
Open `index.html` in a modern browser. No build step, server, external assets, or dependencies are required.

## Prototype features
- Canvas-rendered 2D side-scrolling action platformer.
- Procedurally animated R15-inspired humanoid; animation is prioritized over detailed character art.
- Movement, jumping, sliding, melee attack, energy ultimate, health and energy cells.
- Enemies, NPC dialogue, level guardian and 12-level chapter progression.
- Switchable movement-mode prototypes: run, ship, ball, UFO, wave, robot, spider, jetpack and car.
- Community level JSON import/export and in-game object placement.
- Community skin color editor with JSON import/export.

## Controls
- A/D or arrows: move
- Space/W/Up: jump
- S/Down: slide
- J: forearm-blade attack
- K: ultimate (requires 100 energy)
- E: talk to nearby NPC
- P: pause

## Community levels
Exported files use `format: "roboheckers-level"`, `version: 1`, and an `objects` array. Supported object types: `platform`, `cell`, `enemy`, `npc`, `boss`. See `examples/neon-outskirts.json`.

## Community skins
Skin JSON uses `format: "roboheckers-skin"`, `version: 1`, `primary`, and `accent`. The prototype currently supports color customization; layered pixel/voxel-style R15-compatible textures are a future extension.

## Roadmap
1. Refine physics, collision, touch controls and animation blending.
2. Implement distinct physics and controls for each movement mode.
3. Add chapter narrative, quests, save data, equipment and upgrade trees.
4. Expand editor with grid snapping, object properties, playtest and validation.
5. Add community publishing, moderation, versioning and downloadable skin packs.
6. Add audio, accessibility options, performance testing and automated tests.

This is an early playable prototype, not the complete feature list. Combat feedback is stylized and non-graphic. Treat imported community files as untrusted data and validate them before online sharing.
