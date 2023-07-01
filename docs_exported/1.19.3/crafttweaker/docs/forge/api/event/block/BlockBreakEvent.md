# BlockBreakEvent

The event is not cancelable.

The event does not have a result.

## Importing the class

It might be required for you to import the package if you encounter any issues (like casting an Array), so better be safe than sorry and add the import at the very top of the file.
```zenscript
import crafttweaker.forge.api.event.block.BlockBreakEvent;
```


## Extending BlockEvent

BlockBreakEvent extends [BlockEvent](/forge/api/event/block/BlockEvent). That means all methods available in [BlockEvent](/forge/api/event/block/BlockEvent) are also available in BlockBreakEvent

## Properties

|   Name    |                       Type                       | Has Getter | Has Setter |
|-----------|--------------------------------------------------|------------|------------|
| expToDrop | int                                              | true       | true       |
| player    | [Player](/vanilla/api/entity/type/player/Player) | true       | false      |

