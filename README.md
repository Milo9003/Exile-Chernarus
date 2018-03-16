# Exile.Chernarus for 1.0.4

This is based on kuplion's Exile.Chernarus for 1.0.3

I simply just added new the new things from Exile 1.0.4

## Requirements

* [CUP-Terrains-Core](https://steamcommunity.com/sharedfiles/filedetails/?id=583496184)
* [CUP-Terrains-Maps](https://steamcommunity.com/sharedfiles/filedetails/?id=583544987)
* [Exile 1.0.4](http://www.exilemod.com)

### Optional

* [PBOManager](http://www.armaholic.com/page.php?id=16369)

## Installation

1. Download this repository as a zip file.
2. Extract it to your desktop or somewhere else
3. Drag Exile.Chernarus.pbo to your servers MPMissions folder
4. Edit your configs to use Exile.Chernarus as the mission file.
5. Drag exile_server_config.pbo to @ExileServer/Addons folder and replace the previous.

## Information

To edit the loot spawns, download [PBOManager](http://www.armaholic.com/page.php?id=16369) and [Loot Table Compiler](http://www.exilemod.com/downloads/)

Edit the loot to your liking and then replace the section called 'class CfgExileLootServer' located in exile_server_config.pbo

<hr>

If you want to disable VirtualGarage, Grinding or Hacking

You will find the option to disable those features in config.cpp in the mission file

In config.cpp mission file search for:


### CfgVirtualGarage
```
To disable change enableVirtualGarage = 1; to enableVirtualGarage = 0;
```

### CfgGrinding
```
To disable change enableGrinding = 1; to enableGrinding = 0;
```

### Cfg Hacking
```
To disable change enableHacking = 1; to enableHacking = 0;
```
## Credits

[Kuplion](http://www.exilemod.com/profile/66788-kuplion/) (Exile Forums)

[Kuplion](https://github.com/kuplion) (Github Profile)

[Exile-Chernarus](https://github.com/kuplion/Exile-Chernarus) (His github repository)

# Note

Features Exile Escape, but not guaranteed to work properly
