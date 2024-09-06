# ModSaveBackups

Intended to be used mainly by modders as a dependency, but can also be used by players. Currently, mods that use the ModSave class from the SailwindModdingHelper mod only have one .save file created which will be used across the current save and all backups within a save slot. Using this mod will create backups of any .save file generated by a mod that uses ModSave when the game makes backups of the main save file. If you load a backup save then the corresponding backup ModSave .save file will be loaded.

### Requires
* [BepInEx 5.4.23](https://github.com/BepInEx/BepInEx/releases)
* [SailwindModdingHelper 2.0.3](https://thunderstore.io/c/sailwind/p/App24/SailwindModdingHelper/)

### Installation
Place the ModSaveBackups.dll into the Sailwind/BepInEx/Plugins folder.