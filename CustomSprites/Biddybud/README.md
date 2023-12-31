# Biddybud & Para-Biddybud v1.0.0
*by Nin0 & Baddy, updated by Synel*


## Requirements
- Knowledge about how to install this kind of stuff (at least the basics)
- Kamek 1.3.X (changes may have to be made for Newer 1.2.X)
- [More sprites](https://github.com/Synell/NSMBW-Custom-Sprites/releases/tag/MoreSprites) by AboodXD & Nin0
- [More SFX](https://github.com/Synell/NSMBW-Custom-Sprites/releases/tag/MoreSFX) by Asu (converted by Synel for Newer 1.3.X) and how to use it
- [Path Controller](https://github.com/Synell/NSMBW-Custom-Sprites/releases/tag/PathController) by Nin0
- [Sprite Data Utils](https://github.com/Synell/NSMBW-Custom-Sprites/releases/tag/SpriteDataUtils) by RedStoneMatt and Synel


## Kamek
- Add `src/tentenWing.cpp` and `src/tenten.cpp` in your `src` folder
- Add `tenten.yaml` in your `Kamek` folder
- Reference the `tenten.yaml` in your `NewerProject.yaml`
- Reference the 2 new sfx like this in the sfx list (replace XXXX and YYYY by the correct ids):
```cpp
"tenten_step_l",      // XXXX
"tenten_step_r",      // YYYY
```
- Define the two following variables (replace XXXX and YYYY by the correct ids):
```cpp
#define SFX_TENTEN_STEP_L XXXX
#define SFX_TENTEN_STEP_R YYYY
```
- Add the code for the "more sprite stuff" using `Tenten` and `TentenWing` both for the ProfileID and SpriteID
- Compile your code


## Game
- Add the arc files into the `SpriteTex` folder
- Add the 2 sfx into your `Music/sfx` folder


## Reggie
- Add the content of `spritedata.xml` into your `spritedata.xml` like every other sprites (replace XXX by the sprite ID)
- Add the content of `sprites.py` into your `sprites.py` like every other sprites (replace XXX by the sprite ID)
	> ⚠️ and don't forget to reference the 2 new classes in the list at the end ⚠️
- Add the images in the `sprites` folder into your `sprites` folder
- Restart reggie to apply the changes


*If I forgot some stuff or if you find a bug, be free to let me know*
