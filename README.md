i# Maze project

## Background Context
The goal of this project is to create a game in 3D using raycasting!

You don’t have to do the tasks in order, except for the first one (obviously), or if a task depends on a previous one.

You have a link to a very good and very long tutorial about raycasting in the Tips and links section below, so read it very carefully, and practice!

Please have a lot of fun doing this project!

## Requirements

### General
- All your files will be compiled on Ubuntu 14.04 LTS, using gcc (Ubuntu 4.8.4-2ubuntu1~14.04) 4.8.4.
- We will use the gcc flags -Wall -Werror -Wextra and -pedantic.
- All your functions must be commented.
- Your functions should be maximum 40 lines long (one statement per line).
- Your functions should be maximum 80 columns long.
- No more than 5 functions per file.
### About SDL2 

Simple DirectMedia Layer is a cross-platform development library designed to provide low level access to audio, keyboard, mouse, joystick, and graphics hardware via OpenGL and Direct3D. It is used by video playback software, emulators, and popular games including Valve's award winning catalog and many Humble Bundle games.

## Instalation 
```sh
$ git clone https://github.com/danielaloperahernandez/The-Maze.git
```
## Usage 
* Execute ./maze or type make run 
* Use up and down arrow keys to move forward and backward (keys w and s serve the same function)
* Use right and left arrow keys to turn the camera arround (keys d and a serve the same function)

## Compilation
```sh
$ gcc -Wall -Werror -Wextra -pedantic ./src/*.c -lm -o maze `sdl2-config --cflags` `sdl2-config --libs`;
```

