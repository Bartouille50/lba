# Lonesome BuilderCraft API (LBA) for Minecraft ComputerCraft Turtles

## Disclaimer
** This API is not linked to ComputerCraft mod for Minecraft (http://computercraft.info). Do not report here questions and bugs about ComputerCraft and do not report there questions and bugs about lba

I'll appreciate if you keep credit me if you use or fork this api ^^

You can visit the french website for lba : http://www.liqueurdetoile.com/gaming/lba
You can also visit my franch youtube channel : https://www.youtube.com/channel/UCUavPLdEJR3CL5mIUrSmpX

## Features
Lba extends native computercraft turtles's controls in many ways :
### Version 1.0b
- Full parameters access for control each underlying functions
- Logging system with four levels of messages used by error control
- GPS or self relative coordinates
- Moving API with error control and coordinates update
- Fuel API with error control and autorefuel feature
- Materials API with error control, autodetect and autorefill features
- Build API with light error control, dot, 3D line and X,Z rectangle (hollow and filled) features

## How to Install to your turtle with terminal
- Version 1.0b : `pastebin get UY94nJwL lba`

## How to use it
For using lba, simply provide `your_build()` function with your building script. Lba is designed for building layers from bottom to top (turtle always place blocks from below). As an example, the script is provided with a xmobtower script

Next, you'll need at least to modify fuelLocation and materialLocation parameters for turtle to know where to find fuel and materials.

Code is heavily commented so please refer to it for further explanations about how it's working.

##Todo
- UI for entering fuel and materials position at launch rather than hard coding these
- Full Bug testing
- Code optimization
- add support to put some blocks from front (torches, ladders...)
- Add some build functions : 2D shapes (circle, triangles), 3D shapes (sphere, pyramid)
- Add a matrix build based on file reading
- Add an external visual editor for designing buildings
