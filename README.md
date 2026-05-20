# TB-Trials

Trailblazers: Trials is being built on top of the Godot RTS foundation from
[lampe-games/godot-open-rts](https://github.com/lampe-games/godot-open-rts).

This repo now contains the editable Godot project foundation, including:

- isometric 3D RTS camera and map flow
- terrain and air navigation
- unit selection, production, construction, and combat systems
- resources, fog of war, minimap, AI, and HUD scaffolding
- manual test scenes for validating core RTS behavior

The next layer is replacing the stock sci-fi prototype content with the
Trailblazers anime fantasy world: characters, factions, buildings, resources,
maps, UI treatment, audio, VFX, and progression.

## Upstream Foundation

The original Open RTS README is preserved at
`docs/upstream/godot-open-rts-README.md`.

This local checkout has an `open-rts` git remote pointing to the upstream
foundation. If you clone the repo somewhere else, add it with:

```bash
git remote add open-rts https://github.com/lampe-games/godot-open-rts.git
```

Future foundation updates can then be inspected with:

```bash
git fetch open-rts
git log --oneline main..open-rts/main
```

## Godot Version

The imported foundation targets Godot 4.3.
