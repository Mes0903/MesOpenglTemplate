This is a template of Opengl Project on Windwos10, use CMake and Vscode.

If you wanna use this template, you should copy the `lib` file and dll file by yourself.

# lib folder

There are 3 thing in `lib` folder
1. glfw3.lib  
    u can follow the [learnopengl](https://learnopengl.com/Getting-started/Creating-a-window) website to build it by Visual Studio, and it will in the `build\src\Debug` folder.

    For me, I download the glfw-3.3.8, thus the glfw3.lib is under the folder `D:\glfw-3.3.8\build\src\Debug`, copy it to here.
2. opengl32.dll  
    it's under the folder `C:\Windows\System32`, copy it to here.
3. OpenGL32.Lib  
    it's under the folder `C:\Program Files (x86)\Windows Kits\10\Lib\10.0.17763.0\um\x64` (or x86, depends on what u build), copy it to here.

# include folder

There are 3 thing in `include` folder
1. glad  
    it's under the GLFW folder u download, for me, it's under the folder `D:\glfw-3.3.8\include\GLFW`, copy it to here.

2. GLFW and KHR  
    it's made by the [GLAD](https://glad.dav1d.de/), copy it to here.

# src folder

there is at least one file `glad.c` in the folder, it's under the `glad/src` folder u download before, copy it to here.
