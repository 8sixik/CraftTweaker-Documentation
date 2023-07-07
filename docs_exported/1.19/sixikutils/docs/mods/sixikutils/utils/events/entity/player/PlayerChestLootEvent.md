# PlayerChestLootEvent

The event is not cancelable.

The event does not have a result.

## Importing the class

It might be required for you to import the package if you encounter any issues (like casting an Array), so better be safe than sorry and add the import at the very top of the file.
```zenscript
import mods.sixikutils.api.events.entity.player.PlayerChestLootEvent;
```


## Extending Event

PlayerChestLootEvent extends [Event](/forge/api/event/Event). That means all methods available in [Event](/forge/api/event/Event) are also available in PlayerChestLootEvent

## Methods

:::group{name=getContext}

Return Type: [LootContext](/vanilla/api/loot/LootContext)

```zenscript
// PlayerChestLootEvent.getContext() as LootContext

myPlayerChestLootEvent.getContext();
```

:::

:::group{name=getInventory}

Return Type: [Container](/mods/sixikutils/utils/world/ExpandContainer)

```zenscript
// PlayerChestLootEvent.getInventory() as Container

myPlayerChestLootEvent.getInventory();
```

:::

:::group{name=getPlayer}

Return Type: [Player](/mods/sixikutils/utils/entity/type/player/ExpandPlayer)

```zenscript
// PlayerChestLootEvent.getPlayer() as Player

myPlayerChestLootEvent.getPlayer();
```

:::

:::group{name=getPos}

Return Type: [BlockPos](/vanilla/api/util/math/BlockPos)

```zenscript
// PlayerChestLootEvent.getPos() as BlockPos

myPlayerChestLootEvent.getPos();
```

:::

:::group{name=getQueriedLootTableId}

Return Type: [ResourceLocation](/vanilla/api/resource/ResourceLocation)

```zenscript
// PlayerChestLootEvent.getQueriedLootTableId() as ResourceLocation

myPlayerChestLootEvent.getQueriedLootTableId();
```

:::


## Properties

|   Name    |                               Type                               | Has Getter | Has Setter |
|-----------|------------------------------------------------------------------|------------|------------|
| inventory | [Container](/mods/sixikutils/utils/world/ExpandContainer)        | true       | false      |
| player    | [Player](/mods/sixikutils/utils/entity/type/player/ExpandPlayer) | true       | false      |
| pos       | [BlockPos](/vanilla/api/util/math/BlockPos)                      | true       | false      |

