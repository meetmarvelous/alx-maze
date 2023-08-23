
# The Maze
The Maze is a 3D Maze game that uses ray casting to render a 2D map into a 3D navigable world using raycasting!

The Maze was written was written in C using SDL2 library. Deveploment was performed using Ubuntu 14.04 LTS - gcc (Ubuntu 4.8.4-2ubuntu1~14.04) 4.8.4

The purpose of this project is  to learn the mathematics and physics behind developing the game and learn computer graphics concepts like how to render ,also to learn how to develop a game without a game engine, without using the best free game engine like Unity or Unreal.

### About SDL2 
* Simple DirectMedia Layer is a cross-platform development library designed to provide low level access to audio, keyboard, mouse, joystick, and graphics hardware via OpenGL and Direct3D. It is used by video playback software, emulators, and popular games including Valve's award winning catalog and many Humble Bundle games.
* SDL officially supports Windows, mac 0S X, Linux, ios, and Android. 
* SDL is written in C, works natively with C++, and there are bindings available for several other languages.
* It gives an api for processing video ,audio processing, etc.

## Instalation 
```sh
$ git clone https://github.com/meetmarvelous/alx-maze.git
```

# Usage
* compile using make or make build
* Execute ./maze or type make run
* Use up and down arrow keys to move forward and backward (keys w and s serve the same function)
* Use right and left arrow keys to turn the camera arround (keys d and a serve the same function)

## Compilation
```sh
$ gcc -Wall -Werror -Wextra -pedantic ./src/*.c -lm -o maze `sdl2-config --cflags` `sdl2-config --libs`;
```
# Contribute
* Contributions are always welcome!


## Flowchart
![The Maze Flow Chart](https://i.imgur.com/t0MxNni.png)

## Demo
[![The Maze Demo](https://i.imgur.com/5Ss7s1S.png)](https://www.youtube.com/embed/6T2N8gNUTQ8)