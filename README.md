# ModSaveBackups

This Sailwind mod is intended to be used mainly by modders as a dependency, but can also be used by players. Using this mod will create backups of any mod that generates a .save file using the ModSave class from the SailwindModdingHelper mod. The backups are created when the game makes backups of the main save file. If you load a backup save then the corresponding backup ModSave .save file will be loaded.

### Requires
* [BepInEx 5.4.23](https://github.com/BepInEx/BepInEx/releases)
* [SailwindModdingHelper 2.0.3](https://thunderstore.io/c/sailwind/p/App24/SailwindModdingHelper/)

### Installation
Place the ModSaveBackups.dll into the Sailwind/BepInEx/Plugins folder.