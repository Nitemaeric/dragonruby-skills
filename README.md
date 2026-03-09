# dragonruby-skills

A collection of [Claude Code](https://claude.ai/claude-code) skills for building games with [DragonRuby GTK](https://dragonruby.org).

## Install

```sh
npx skills add nitemaeric/dragonruby-skills
```

Or install a single skill:

```sh
npx skills add nitemaeric/dragonruby-skills/tree/main/skills/dragonruby-platformer
```

## Skills

| Skill | Description |
|---|---|
| `dragonruby` | Core API — tick loop, state, outputs, inputs, geometry, audio, easing, layout, runtime |
| `dragonruby-rendering` | Render targets, cameras, HD/lowrez display, pixel arrays, blendmodes, viewport culling |
| `dragonruby-audio` | Spatial audio, crossfading, procedural synthesis, beat sync, audio queues |
| `dragonruby-3d` | Raycasting, Mode7, matrix math, sprite-based 3D, wireframe rendering, VR patterns |
| `dragonruby-pathfinding` | A*, BFS, flow fields, flood fill, line-of-sight, spatial hashing, quad trees |
| `dragonruby-ui` | Buttons, checkboxes, scroll views, menus, input remapping, tooltips, accessibility |
| `dragonruby-platformer` | Physics, AABB collision, action state machines, variable jump, moving platforms, combo inputs |
| `dragonruby-yard` | Solargraph LSP setup for IDE autocomplete and type support via YARD stubs |

## Manual install (symlink)

```sh
git clone https://github.com/nitemaeric/dragonruby-skills
ln -s $(pwd)/dragonruby-skills/skills/dragonruby ~/.claude/skills/dragonruby
# repeat for each skill you want
```
