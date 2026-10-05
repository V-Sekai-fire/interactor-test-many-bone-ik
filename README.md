# interactor-test-many-bone-ik

A game-engine test project that poses rigged characters with a many-bone inverse-kinematics solver and its joint constraints.

## What it is for

It holds a few rigged characters and scenes that drive their skeletons through the multi-chain IK node, for checking pins, constraints and solver changes by eye. It needs an engine build that includes that IK module.

## Build and run

```sh
git submodule update --init
```

Then open `project.godot` in the engine's editor.

## Licence

MIT; see `LICENSE`. The character models carry their own licence files.
