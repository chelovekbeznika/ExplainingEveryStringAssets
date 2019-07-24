# explainingeverystringassets
This repository belongs to youtube channel "explaining every string" and keeps assets for game with same title.
[Link to code repository](https://github.com/chelovekbeznika/ExplainingEveryString)
## Necessary folder structure
There are two repositories and they require recreating next folder structure to work correctly:
* Build
* Source
   * ExplainingEveryString [CODE REPOSITORY HERE](https://github.com/chelovekbeznika/ExplainingEveryString)
* ExplainingEveryStringAssets (THIS REPOSITORY HERE)
## How to add/edit sprite
1. Draw it in aserprite and save in Raw/Sprites in appropriate subfolder or edit existing folder
2. Export it as spritesheet in Ready/Sprites in appropriate subfolder
3. Add it to mgcb project in Monogame Pipeline tool
4. If sprite animated - add info about frames amount in assets_metadata.dat
## How to add/edit other assets
1. Create and save "source" or "preexported" version in "Raw" folder if necessary.
2. Export/save ready for adding to mgcb project assets in "Ready" folder.
3. Add it to mgcb project
