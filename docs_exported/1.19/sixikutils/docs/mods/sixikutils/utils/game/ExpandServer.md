# ExpandServer

## Importing the class

It might be required for you to import the package if you encounter any issues (like casting an Array), so better be safe than sorry and add the import at the very top of the file.
```zenscript
import crafttweaker.api.game.Server;
```


## Implemented Interfaces
ExpandServer implements the following interfaces. That means all methods defined in these interfaces are also available in ExpandServer

- [CommandSource](/vanilla/api/command/CommandSource)
- AutoCloseable

## Methods

:::group{name=getOwnerPlayer}

Allows you to get the owner of the server if the server is started from the world. That is, it was open to the network

Return Type: [Player](/mods/sixikutils/utils/entity/type/player/ExpandPlayer)

```zenscript
// Server.getOwnerPlayer() as Player

myServer.getOwnerPlayer();
```

:::


## Properties

|    Name     |                               Type                               | Has Getter | Has Setter |                                                      Description                                                       |
|-------------|------------------------------------------------------------------|------------|------------|------------------------------------------------------------------------------------------------------------------------|
| ownerPlayer | [Player](/mods/sixikutils/utils/entity/type/player/ExpandPlayer) | true       | false      | Allows you to get the owner of the server if the server is started from the world. That is, it was open to the network |

