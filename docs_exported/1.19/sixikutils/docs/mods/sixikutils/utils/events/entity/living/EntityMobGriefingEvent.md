# EntityMobGriefingEvent

The event is not cancelable.

The event does not have a result.

## Importing the class

It might be required for you to import the package if you encounter any issues (like casting an Array), so better be safe than sorry and add the import at the very top of the file.
```zenscript
import mods.sixikutils.api.events.entity.EntityMobGriefingEvent;
```


## Extending EntityEvent

EntityMobGriefingEvent extends [EntityEvent](/forge/api/event/entity/EntityEvent). That means all methods available in [EntityEvent](/forge/api/event/entity/EntityEvent) are also available in EntityMobGriefingEvent

## Methods

:::group{name=getEntity}

Return Type: [Entity](/vanilla/api/entity/Entity)

```zenscript
// EntityMobGriefingEvent.getEntity() as Entity

myEntityMobGriefingEvent.getEntity();
```

:::


