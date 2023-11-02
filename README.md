# TaitrussBuilds
### Build Version: 1.1

#### [Project Source Code](https://github.com/phoenixjmh/Taitruss)

##### Install instructions
- Download setup.exe and setup.msi
- run setup.exe
  

## Project Goal
The goal of this project is to create a Tetris clone, aiming for similarity to the original NES version. The challenge is to accomplish this without utilizing any external resources like online tutorials or searches. The objective is to enhance my understanding of the intricate aspects of C++ and program structure. All resources within this project are created by myself, and all sound assets are produced by Damien Mallette.

This is technically not from "scratch" as SDL was used, but no other frameworks/libraries are used here.

### Logic
- Similar to NES tetris, there is no kickout on rotation. When attempting a rotation against a wall, the rotation will simply be disabled. 
- You get exactly one tick to make your desired move if you're on top of another block. Newer tetris versions give you about 3-4 ticks, even more if you're rotating or moving. That is not the case here.

## Highscores
-----------------
- Cassie: 4060
