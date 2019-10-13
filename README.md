# LosslessSprite

This is a png image segmentation / splitter that does lossless cutting of images.
It is written using the Python png module and runs an n^2 algorithm.
Each non-transparent pixel will be connected to its neighbors, and when there are no more neighbors the obtained pixels
will be "cut" and put into a new png image file.
This process repeats until all images are extracted.

Included are the sprite sheet that I cut and the results in the tileset folder.
