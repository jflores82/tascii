# Tascii Level Editor
Tascii (read as Tasky) is a online ASCII level creator/editor, coded in Javascript. 
It was designed to fill a gap that i couldn't find in other ASCII Level editors, which is editing the output format, in my case, i wanted to created levels that i could copy + paste directly into a Lua list, to use in my game's code. And none of the editors i found allowed that, which meant creating the layout, copying, and then pasting + editing, instead of just copying + pasting directly into my game code. 

I also added a "map_index" which is a counter that goes up every time you export a level, so you can work in sequence with several levels and they will be numbered correctly in a C or Lua array. 

And i've made so that you can edit this format, so i can keep using this for another game, if the need arises. 

You can also add a linebreak before the generated level.

You can click/drag on the grid to draw a tile.

## Screenshots
![Tascii 01](https://classicgames.com.br/site/img/tascii1.png)

![Tascii 02](https://classicgames.com.br/site/img/tascii2.png)

## Instructions
- To place a tile, simply click on the grid. 
- To select a new type of tile, you can just press the key you want. It will auto-fill the "Tile" field.
- You can change the width/height of the grid as desired. 
- You can clear the field (and it will be replaced by the tile selected in "Default Tile").
- And to copy, you can simply click the button or select and copy the text in the output box.

## Releases 
Version 4 (20260312):
- Fixed bug with "Clear Layout" button not loading default tile.

Version 3 (20260224):
- Added option to append the level to the current output.

Version 2 (20260223):
- Fixed issue #1 - double dollar sign rendering as a single dollar sign.

Version 1 (20260220):
- First Public Release
 
## License
This project is licensed under the **MIT License**, except where noted below.

- The **source code** is licensed under the [MIT License](LICENSE).

## Contributor License Agreement (CLA)

By submitting a pull request, you agree that:
- Your contribution is your own original work.
- You grant the project maintainer(s) a perpetual, worldwide, non-exclusive license to use, reproduce, and distribute your contribution under the project's existing license (MIT).
- You understand that your contribution will be made publicly available as part of the project.

## Disclaimer
The software is provided “as is”, without any warranty.  
The author shall not be held responsible for any damages, misuse, or modifications of the code or assets.
**NO AI WAS USED IN MAKING THIS SOFTWARE**