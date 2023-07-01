# EnderPearlTeleportEvent

The event is not cancelable.

The event does not have a result.

## Importing the class

It might be required for you to import the package if you encounter any issues (like casting an Array), so better be safe than sorry and add the import at the very top of the file.
```zenscript
import crafttweaker.forge.api.event.entity.teleport.EnderPearlTeleportEvent;
```


## Extending EntityTeleportEvent

EnderPearlTeleportEvent extends [EntityTeleportEvent](/forge/api/event/entity/teleport/EntityTeleportEvent). That means all methods available in [EntityTeleportEvent](/forge/api/event/entity/teleport/EntityTeleportEvent) are also available in EnderPearlTeleportEvent

## Properties

|     Name     |                                   Type                                   | Has Getter | Has Setter |
|--------------|--------------------------------------------------------------------------|------------|------------|
| attackDamage | float                                                                    | true       | true       |
| hitResult    | [HitResult](/vanilla/api/util/HitResult)?                                | true       | false      |
| pearlEntity  | [ThrownEnderpearl](/vanilla/api/entity/type/projectile/ThrownEnderpearl) | true       | false      |
| player       | [ServerPlayer](/vanilla/api/entity/type/player/ServerPlayer)             | true       | false      |

