# Shaders Reborn v0.2

# FAREWELL
#### I will probably be leaving this project as i don't have time to maintain it and i really fucked something up that I do no understand. I hope y'all can have fun with what it is right now and maybe you guys can update it, i will be checking on this and merge pull requests if needed :)

![options menu](https://github.com/wxnnvs/ShadersReborn/blob/main/Plugins.png?raw=true)

# Progress so far:
|Task|Progress|
|---|---|
|Update Plugin API (a4.3 -> a5.1)|🟠 In progress|
|Implement AutoEagler as alternative to singleplayer|🟠 In Progress|
|Port Java support|🟠 In Progress|
|Restyle Plugin Manager|⚪ Soon|

### This repository contains:

 - **Utilities to decompile Minecraft 1.8 and apply patch files to it**
 - **Source code to provide the LWJGL keyboard, mouse, and OpenGL APIs in a browser**
 - **Patch files to mod the Minecraft 1.8 source code to make it browser compatible**
 - **Browser-modified portions of Minecraft 1.8's open-source dependencies**

### This repository does NOT contain:

 - **Any portion of the decompiled Minecraft 1.8 source code or resources**
 - **Any portion of Mod Coder Pack and it's config files**
 - **Data that can be used alone to reconstruct portions of the game's source code**
 - **Software configured by default to allow users to play without owning a copy of Minecraft**

## Getting Started:

### To compile the latest version of the client, on Windows:

1. Make sure you have at least Java 11 installed and added to your PATH
2. Download (clone) this repository to your computer
3. Double click `CompileLatestClient.bat`, a GUI resembling a classic windows installer should open
4. Follow the steps shown to you in the new window to finish compiling

### To compile the latest version of the client, on Linux/macOS:

1. Make sure you have at least Java 11 installed
2. Download (clone) this repository to your computer
3. Open a terminal in the folder the repository was cloned to
4. Type `chmod +x CompileLatestClient.sh` and hit enter
5. Type `./CompileLatestClient.sh` and hit enter, a GUI resembling a classic windows installer should open
6. Follow the steps shown to you in the new window to finish compiling

## Credits
- OtterDev102: Creator of Eagler Reborn, wrote java support
- zxmushroom63: Wrote Plugin API
- wxnnvs (me): Porting Plugin API