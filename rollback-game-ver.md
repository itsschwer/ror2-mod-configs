# rollback

1. `win`+`r` → `steam://nav/console`
2. `download_depot 632360 632361 9058106608706845920` *(Devotion Update)*
    - *this may take a while; the Steam Console will not print any progress updates (until finished)*
    - will download to `\Steam\steamapps\content\app_632360\depot_632361`
3. Delete everything in the game folder
4. Copy contents of the downloaded depot into the game folder
    - *`\Steam\steamapps\common\Risk of Rain 2`*
5. ~~Disable *Automatic updates* for the game~~
    - ~~*Otherwise Steam will try to update the game when it launches?*~~

### syntax
```
download_depot <APP_ID> <DEPOT_ID> <MANIFEST_ID>
```

## refs
- https://steamcommunity.com/sharedfiles/filedetails/?id=3023295121
- https://github.com/risk-of-thunder/RoR2VersionSelector
