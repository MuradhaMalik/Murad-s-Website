---
layout: default
---
## Coding Secrets
### Custom Movement Blocks/Functions
Heres a coding secret if you are using a xdrive/mechanum drive or some other wierd drive type. im doing it in blocks for simplicity but itl work in c++ as a func and a smth. 
make a "myblock" and name it smth like driveforward. add a number input as rotations. drag all your chassis motor blocks in as forward, and replace the number of rations with the 
round number input. repeat this a bunch of times until you have forward, back, turn left, turn right, strafe left (if applicable) and strafe right (if applicable) change the 
move type (forward, back) accordingly. now you have a custom driving block!!
