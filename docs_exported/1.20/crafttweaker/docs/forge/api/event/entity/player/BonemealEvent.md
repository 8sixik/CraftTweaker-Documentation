# BonemealEvent

The event is not cancelable.

The event does not have a result.

## Importing the class

It might be required for you to import the package if you encounter any issues (like casting an Array), so better be safe than sorry and add the import at the very top of the file.
```zenscript
import crafttweaker.forge.api.event.entity.player.BonemealEvent;
```


## Extending PlayerEvent

BonemealEvent extends [PlayerEvent](/forge/api/event/entity/player/PlayerEvent). That means all methods available in [PlayerEvent](/forge/api/event/entity/player/PlayerEvent) are also available in BonemealEvent

## Properties

| Name  |                    Type                     | Has Getter | Has Setter |
|-------|---------------------------------------------|------------|------------|
| block | [BlockState](/vanilla/api/block/BlockState) | true       | false      |
| level | [Level](/vanilla/api/world/Level)           | true       | false      |
| pos   | [BlockPos](/vanilla/api/util/math/BlockPos) | true       | false      |
| stack | [IItemStack](/vanilla/api/item/IItemStack)  | true       | false      |

