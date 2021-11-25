# Pattern Matcher
## What it is
Pattern matcher is an arcade game that allows users to test their memorization skills. The users job is to match a  randomized light pattern by pressing its corresponding button. If correct, the game moves forward and shows the user the next part of the pattern. This process continues until the user successfully matches the complete pattern. In the case that the user presses the incorrect button, the game flashes a red LED and the users' is prompted to try again.

## Demo
<img src="https://github.com/Samanthatb1/Pattern-Matcher-STM32/blob/main/docs/fullGame.gif" width="600px">


## How it works
The game is built on an STM32 Nucleo. The lifetime of the code begins with the user turning on the microcontroller, in which the game starts and an array is initialized to hold a randomized combination of LEDs. The lights are then turned on in order, and the user is prompted to click a button that corresponds to the light. Each round the user must input one additional index of the array. The loop is broken once the user clicks the incorrect button, and they are then prompted to click the reset button to play again. 

## Inspiration
Designed for ECE 198 at the University of Waterloo

Created by Samantha Grieco and Maham Ali