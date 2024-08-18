## ayaka mod + 冰霧切

[gamebanana](https://gamebanana.com/mods/529469)

## UID hidden

[gamebanana](https://gamebanana.com/mods/431307)

```ini
[Constants]

global persist $HideUID = 1

[KeySwitch]

key = alt F11

type = cycle

$HideUID = 0,1

[TextureOverrideUid]

hash = 83fd403f

match_first_index = 0

run = CommandListUID

[CommandListUID]

if $HideUID == 1

handling = skip

endif
```

**Instructions:**

1. Delete all content in the original `.ini` file and replace it with the above configuration.
2. Use `Alt + F11` to toggle the UID on and off. It is hidden by default.
3. Note: This mod no longer affects the stamina bar.

## RemoveTransparencyFilter for 4.8

[gamebanana](https://gamebanana.com/mods/529138#FileInfo_1241035)

## Remove Underwater Censorship

[gamebanana](https://gamebanana.com/mods/462790#FileInfo_1238141)
