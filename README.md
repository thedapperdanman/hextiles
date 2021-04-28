# hextiles
Hex tiles for Tabletop Simulator


This is a repository for models and texture image files for loading hexagonal shaped tiles into your Tabletop Simulator game. You can use the TIFF file to see how to create custom texture images for the models. 

To load into TTS make sure you have the following files

1. OBJ file for the model
  example - two-hexes.obj
  
2. Texture file
  example - two-hex_2048px.png
  Use the TIFF file for reference in making the texture image and save as a flattened PNG for uploading into TTS
  
3. Collider file
  example - two-hexes_collider.obj
  This file will be used to create a custom shape collider for your object. This is needed if your model object is not a rectangular volume of some sort. For this instance, the convex sections between the hexagonal points require a collider model to allow the tiles to fit in the empty spaces.
