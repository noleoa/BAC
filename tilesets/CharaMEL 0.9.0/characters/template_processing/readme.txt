This is a template for processing existing character sprite images with "Caramel -CharaMEL-".



■ Editing "character.json"

First, set the "character.json" file to match the standard for the character sprite image you wish to use.
The items to be edited are as follows.

This is the overall image size.

"ImageSize": "Vector2( 96, 128 )",

96 is the horizontal size and 128 is the vertical size. This is the overall image size of your character sprite image.


This is the image size of one character sprite pattern.

"SpriteSize": "Vector2( 32, 32 )",

The first 32 are the horizontal size and the next 32 are the vertical size.


This is the format for character sprites.

"Format": [
	"4-way 3-animation"
],

If you are using "RPG Maker", there is no problem with keeping the "4-way 3-animation". If you want to use 3 patterns in 8 directions in "WOLF RPG Editor", please mention "8-way 3-animation" or "SRPGStudio" for "SRPGStudio" map characters. For a single sprite, such as a face image, use "Picture.



■ Storing image files

Next, store the character sprite images you wish to process in the "images" folder in the "Parts" folder.



■ Launching "CharaMEL"

Start "CharaMEL" and select "Processing Template" from the character set selection menu on the upper left. Then, adjust the colors and apply effects and save the image as a PNG image. The effect cannot be saved, but the color adjustments can be saved as favorites. *If the original sprite image is deleted, the favorite will no longer function.
