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

delete all in original ini and put this
alt+F11 turn on and off. hided by default
No not effect stamina bar anymore

## RemoveTransparencyFilter for 4.8

[gamebanana](https://gamebanana.com/mods/529138#FileInfo_1241035)

## Remove Underwater Censorship

[gamebanana](https://gamebanana.com/mods/462790#FileInfo_1238141)
