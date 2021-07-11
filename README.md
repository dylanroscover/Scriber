# 📖 ✏️ Scriber 
Typography layout, style and animation toolkit in TouchDesigner

## Why
TouchDesigner as a platform has plenty of character, however it lacks out-of-the-box *per*-character text transformations, such as kerning and animation. The aim of this component is to provide TD devs a toolkit to rapidly iterate type for motion graphics animations in TD.

![Scriber](/img/scriberScreenshot1.png)

##  Status
- 📝 Current Implementations
    * Basic kerning
    * Basic animation (in/out)

- 💾 Software
    * TouchDesigner 2021.13610 
    * Tested on Win 10 x64 

## 🚧 Planned Features
- Position/rotations on 2d/3d paths ("Type on a Path")
- Per-character/word transformations
    * colour
    * size
    * weight
    * kerning
    * animations
        * utilizing Phaser CHOP
        * translate (xyz)
        * rotate (xyz)
        * scale (xy)
        * colour (rgba)

## Thanks
- [Elburz](https://interactiveimmersive.io)
- David Braun for Phaser CHOP