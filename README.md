# Windows 7 aero theme for OpenGlass

## Preview: <img width="213" height="94" alt="image" src="https://github.com/user-attachments/assets/9b797758-56d2-4155-b319-46e12f7450be" /> (follow my settings:) <img width="857" height="73" alt="image" src="https://github.com/user-attachments/assets/6443f7d2-55a6-4005-b0b4-61b052adaf32" />


miss the old win7 glass look on windows 10/11? i put together this theme atlas for ALTaleX531's OpenGlass project to bring back the transparent window borders, rounded corners, and glowing buttons.

inside this folder there is the `.png` atlas image and the `.png.layout` file. make sure you keep them in the same folder or openglass won't know how to map the textures.

### Go to releases to download:
check the releases section on the right side of this page to grab the zipped archive package.

### How to use it:
1. drop both files somewhere safe on your PC (like `c:\openglass\themes\`).
2. open `regedit` and go to `HKEY_CURRENT_USER\SOFTWARE\OpenGlass`.
3. find the string value named `CustomThemeAtlas` (create it if it isn't there).
4. change its value to the exact path of the png file.
   * example: `c:\openglass\themes\windows7 theme atlas.png`
5. restart openglass or hit refresh in the gui and it should change instantly.

Shoutout to ALTaleX531 for making OpenGlass! if the borders look weird or clipped on high scaling setups (like 125% or 150%), just open an issue here and i'll try to fix the layout coordinates.
