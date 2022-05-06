# HasTranslation

This class was added by a mod with mod-id `mekanism`. So you need to have this mod installed if you
want to use this feature.

## Importing the class

It might be required for you to import the package if you encounter any issues (like casting an
Array), so better be safe than sorry and add the import at the very top of the file.

```zenscript
import mods.mekanism.api.text.HasTranslation;
```

Any objects implementing this interface have a translation key you can get and use.


## Methods

:::group{name=getTranslationKey}

Gets the translation key for this object.

Return Type: string

```zenscript
// HasTranslation.getTranslationKey() as string

myHasTranslation.getTranslationKey();
```

:::

## Properties

| Name | Type | Has Getter | Has Setter | Description |
|------|------|------------|------------|-------------|
| translationKey | string | true | false | Gets the translation key for this object |

