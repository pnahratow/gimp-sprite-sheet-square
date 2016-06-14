# gimp-sprite-sheet-square

Modification of http://registry.gimp.org/node/20943 to create a square spritesheet instead of a single row.

Creates a new spritesheet (animation frames) from the layers of an image.

1. To install, copy SpriteSheetSquare.scm to {GIMP-HOME}\share\gimp\2.0\scripts\SpriteSheet.scm
2. Either close Gimp and re-open, or simply select menu: Filters > Script-Fu > Refresh Scripts
3. Load your images via File > Open as layers (select all the images you want to in the spritesheet)
4. Optionally re-order your layers to determine ultimate order. Bottom-most layer will be left-most image in final merge.
5. Run menu option Filters > Sprite-Sheet-Square > Create From Layers...

You should end up with a new image that fits the layers you opened next to each other in a square.

* Code License: Public Domain
* Scripting Engine: Script-Fu
