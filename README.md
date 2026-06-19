# Fix Jungle Saplings

Minecraft data pack that raises jungle leaf sapling drops to the standard leaf decay rate used by most other trees.

## What changes

- Overrides `minecraft:blocks/jungle_leaves`.
- Changes jungle sapling chances to `5%`, `6.25%`, `8.3333336%`, and `10%` for Fortune levels 0 through 3.
- Keeps normal jungle leaf drops from shears and Silk Touch.
- Keeps vanilla stick drops.

## Install

Copy this folder into a world's `datapacks` folder, then run `/reload` or reopen the world.

## Release versioning

Pushes to `master` create GitHub releases with semantic version tags like `v1.2.3`.

Commit messages use a small Conventional Commits subset:

- `fix: adjust jungle leaf loot table` bumps the patch version.
- `feat: add another loot table override` bumps the minor version.
- `feat!: change supported Minecraft version` bumps the major version.
- A commit body containing `BREAKING CHANGE:` also bumps the major version.

Commits that do not match `feat:` or a breaking-change marker still create a patch release.
