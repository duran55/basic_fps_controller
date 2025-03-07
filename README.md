# basic_fps_controller

Basic fps controller for Godot 3.x and 4.x

Features include:

- basic movement and jumping
- physics interpolation to reduce jitter on high refresh rate monitors
- solves all weird slope sliding/climbing issues 

Changes of this fork:

- increase air accel to make it more fun
- add bunny hop style jumping: no skills required, just hold the jump button
- add walk action: holding walk button will make the player move slower
- add quit action: quit from the game / project

Suggestions:

- attach FPS.gd to the main node (kinematic body) of FPS.tscn
- names for wasd keybindings are "move_forward" "move_backward" "move_left" and "move_right"
- this is just a character controller, I assume you already have a game world set up to test it out on

Credit: Garbaj
