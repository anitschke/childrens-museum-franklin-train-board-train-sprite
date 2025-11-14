# childrens-museum-franklin-train-board-train-sprite

This is a simple program to aid in building a sprite sheet of a train for [the train arrival board](https://github.com/anitschke/childrens-museum-franklin-train-board) that I built for the [Children's Museum of Franklin](https://www.childrensmuseumfranklin.org/).

![train animation](./trainScaled_black.gif)

## Details
In general it works by using ImageMagick to take some source images/sprites and build them into one final sprite. This allows for easy editing of things like the look of the train as it can rebuild the final massive sprite sheet without having to manually modify each of the frames.

There are two sources.
* `trainSrc.bmp` This is the still of the train and we move forward by one pixel for each frame in the sprite sheet.
* smokeSrc.bmp` This is a looping sprite sheet of smoke coming out of the smoke stack that I manually animated using smokeSingleFrameSrc.bmp. This gets "attached" to the smoke stack and just loops as the train drives forward.