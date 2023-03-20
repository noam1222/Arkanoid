# Arkanoid
## Overview
In this project we create the Arkanoid game base on GUI interface of the Bar-Ilan university. </br>
This is assignment in the oop-course of Bar-Ilan University.

### User Guide
The goal is to eliminate all the blocks on the screen. </br>
Every time ball hit block, the block disappeared. </br>
The control in the balls achieved by moving the paddle in the bootom of the screen by the keyboards left and right arrows. </br>
To pause the game use `p`. To continue, use `SPACE`.

### Levels
There are 4 levels: </br>
Level 1: </br>
![Level 1](https://user-images.githubusercontent.com/101872202/198084543-ee33f5a3-d565-43e2-a130-32522f4f45b9.png) </br>
Level 2: </br>
![Level 2](https://user-images.githubusercontent.com/101872202/198085088-0c3097b2-6a63-4b19-ab7e-ede042fb5d28.png) </br>
Level 3: </br>
![Level 3](https://user-images.githubusercontent.com/101872202/198085404-65a53f68-c334-4d00-8b18-a8ee8c3ceff6.png) </br>
Level 4: </br>
![Level 4](https://user-images.githubusercontent.com/101872202/198085642-1caeab52-32f7-4d7f-9a8d-c1e4610a837d.png) </br>


## run
First, clone the repo. Than use the following commands inside the project folder: </br>
To run this game from level 1 to 4 use the command `ant run`. </br>
To run in any other levels order use the command `ant run -Dargs="levels order"`. For example, to start the game in level 2 and after win it move to level 4 write `ant run -Dargs="2 4"`. </br>
To clean all the compilation files use `ant clean`. </br>
To compile the game without run it use `ant compile`. </br>

### Requirements
- Java.
- Ant.




