# ImageBatch
Download images and put them into a single texture to reduce drawcalls in Defold

- Supports PNG and JPG filetypes
- RGB only for now (will add RGBA support later)
- The included sample tilesource is only 40 slots, you can add more
- The example is 10x10 tilesource with a size of 100x100 for each tile
- You must manually set the properties of the image_controller.script to whatever sizes you want
- You can send messages to the image_controller to load new slots, you can overwrite slots, it's up to you to manage slots
- Image caching is forced right now (will be an option later)
- You can take the code out and use if how you want
- Edge extrusion support will be added later
- More other features will be added later