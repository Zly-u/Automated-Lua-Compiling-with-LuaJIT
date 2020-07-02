# Batch files for automated compilation
Should work with any version of [LuaJIT](https://luajit.org).

To make scripts work you should drag and drop your project directory or a script file you want to compile.

`compile_luac.bat`    - Keeps the original files and puts `.luac` files near by the original ones.

`compile_Replace.bat` - Replacing all original lua scripts with compiled ones.

You can replace `bin` folder with your version of `LuaJIT`'s `bin` folder.

Compiled scripts also work with [Love2D](https://love2d.org).