# SDL Engine v0.25

Latest Changes
---------------
-Expanded IMGUI Support so that it works in any scene in a separate window
-Changed Singletons to Magic Statics (other than FontManager -- still TODO)
-Added more Collision Check Functions in Collision Manager (e.g. LOSCheck)

Known Bugs
---------------
-ImGuiWindowFrame not clearing upon ImGuiWindow move
-When FontManager is converted to Magic Static Singleton type, it crashes app on exit
-UIButton Events a little janky when being clicked

## Previous Versions

### v0.24
---------------
-Added IMGUI Support (see GUI_Function in PlayScene.cpp)

### v0.23
-----
-fixed removeChild bug

### v0.22
-----
-Updated Project to C++ 17
-added removeChild to DisplayList
-added layering to DisplayObject
-added enabling / disabling to GameObject

### v0.21
-----
-Updated to Current Version of SDL 2.0.12
-Updated to SDL Image 2.0.5
-Added SDL net 2.0.1
-removed unused dlls and libs

### V0.20 and earlier
-----------------
- Earliest SDL_Engine Build and Debug
