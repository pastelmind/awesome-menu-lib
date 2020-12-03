# awesome-menu-lib

awesome-menu-lib is an ASH script and library for KoLmafia.
It provides data structures and functions for manipulating KoL's top menu bar icons.
It also provides gCLI commands for saving and restoring your Top Menu Bar presets.

**WARNING: This script is still under development. It may have unexpected bugs and may destroy your current top menu bar settings. Use at your own risk!**

Note: The iconic top menu bar in Kingdom of Loathing is driven by `awesomemenu.php`, which is where this library took its name.

## Installation

Enter the following into KoLmafia's gCLI:

```
svn checkout https://github.com/pastelmind/awesome-menu-lib/trunk/release
```

## Usage

To save your current top menu bar configuration, enter the following into KoLmafia's gCLI:

```
awesome-menu-lib save <config_name>
```

Where `<config_name>` is any name of your choice.

To apply a saved configuration to your current top menu bar, type in:

```
awesome-menu-lib apply <config_name>
```

All configurations are currently saved to `data/awesome-menu-presets.txt`. These presets are shared between your characters.

**WARNING: This command will destroy your current top menu bar settings. Save your top menu bar before running this command.**
