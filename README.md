# base-terrain-feature-ivory

The `Ivory` terrain feature: a special resource a square can hold.

For example: Civ2's Ivory, found on Glacier.

This package only declares the class: it has no `main` and registers nothing, so installing it changes no game.
A game's rules register it and give it its yields.

```ts
import Ivory from '@civ-clone/base-terrain-feature-ivory/Ivory';
import { instance as availableTerrainFeatureRegistryInstance } from '@civ-clone/core-terrain-feature/AvailableTerrainFeatureRegistry';

availableTerrainFeatureRegistryInstance.register(Ivory);
```

Part of the Civ2 work (civ-clone/web-renderer#1008).
