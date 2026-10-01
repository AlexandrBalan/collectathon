A place to write your findings and plans

## Understanding
There is a player size and treasure size with a player speed (changable)

There is a score that starts at 0 (counter)

There is basic controls to move the player

There is a spring player and treasure that are set at different locations

There is a variable called rng that is used to give the treasure a random spawn point

Code for if the player intersects the treasure, give it a random location and up the score by one.


## Planning required changes

1. Find the variable that increases player speed

Change the value to a higher one to increase it.

2. find the variable that is for the background, then insert a hex color and remake the game 
to change the backdrop color.

    Variable was not found. I had to import files in order to change color of background to light blue.

3. Change starting pos of the player and dot using a variable for each cord.

    Made variable of static constexpr for x and y of each character.
    Speed was also changed to a lower amount 

4. Create a if statement for the reset keybind, just create another if statement and just reset the 
x position and the y position, along with the treasure and the score!

5. Probably use the already made variables (MIN_X, MIN_Y, etc) and check to see if the player if above or below those variables. If so, put them opposite side so the player loops

## Brainstorming game ideas

## Plan for implementing game

