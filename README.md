# quake-maps

My custom maps made for quake. I strongly recommend checking out [jonathanlinat's Level-Design Starterkit]https://github.com/jonathanlinat/quake-leveldesign-starterkit)

## Run a map

> quakespasm.exe +map macbeth


#### How do mods work?

> quakespasm.exe -game mymod 

Where `mymod` refers to a folder in the quake directory, similar to the official game's own `ID1` folder.
Each mod folder, include the main one, is considered an override over the defaults. If you want the game to start with a different map or some other keybinds, just add those to a config and put it in your mod folder.

For example, if you downloaded the excellent [Arcane Dimensions mod](http://www.simonoc.com/pages/design/sp/ad.htm) you should unpack it into the Quake directory as a subdirectory, perhaps called `ad`. Then when you launch Quake request that folder `quakespasm.exe -game ad`

## Tools

### Quakespasm

The premier modern Quake 1 engine, with support for coloured lighting, increased limits and some decent mouse support. While the engine is free, maps are still usually based on Quake's original content, contained in PAK0 and PAK1 files. PAK1 is only available in the full version of the game.

### Compiler utils

TyrUtils is a collection of improved Quake tools for compiling maps. 

#### `bsp`

Builds the `.bsp` playable map file from the editable `.map` file you make in Trenchbroom. The map can be played as soon as there is a `.bsp` file, even without calculating lighting and visibility. 

#### `light`

Generates the lightmaps, and if there is coloured lighting it will generate a `.lit` file as well.

#### `vis`

Calculates visibility information, important for good performance.

### Trenchbroom

Modern map-making tool.

### Wally

Old fashioned texture editor for Quake WADs (in Quake WAD files contain textures, not maps).



