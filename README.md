# Pyro ][ Reignited

https://laroo.github.io/Pyro2-Reignited/

Created using Amazon Q: https://builder.aws.com/content/2y6egGcPAGQs8EwtQUM9KAONojz/build-games-challenge-build-classics-with-amazon-q-developer-cli

## Iterations:

First iteration:

Write a HTML/JS game clone of Pyro 2 (PC Game, 1990). Basically you see a 2d floor map with walls and rooms. Goal is to lay down a fuse and drop fire bombs along the fuse. When the fire bombs explode it will burn down near walls. Score is calculated on how many walls are burned down

2nd:

Basic game mechanics work great. Instead of laying the fuse make that will will be automatically layed when the user walks in a line. When key 'f' is pressed the fuse will start igniting from the beginning and slowly burn down the whole layed down fuse and bombs will explode when the fuse burns near them

3rd

Make the bombs gas cans where the gas will spread through between the walls. Once the fuse hits the gas it will burn down the adjacent walls. These ignited walls will keep burning until there is no direct connected walls anymore. This makes the destruction more extreme. Keep score on how many wall blocks are burned and show a percentage of burned wall blocks and total wall blocks

4th

Gas can should only spread out a few block; max of 10 block per gas can

5th

Great. When a gas can is dropped it should spread out slowly. Once the gas is burned change the color.

6th

Fix: all gas cans explode at the same time instead of waiting for the fuse or a near wall exploding. Floorplan generator sometimes causes the user not be able to walk for a few blocks. Make sure there are no wall blocking the user from walking around.

7th

Reducing wall density from 30% to 25% is a bit too much; make it smarter. Slow down burning the walls and animate it. Make sure the user has max 5 gas bombs and add an indicator how many bombs there are left. Start the fuse automatically after 10 seconds if the user didn't start it yet and show a timer. If the fuse reaches the user it's the end of the game. Wait until the fuse and walls are burned and show the final burned percentage and used bombs.

8th

Time for an intro screen with a logo. The game will be called "Pyro ][ Reignited" (reference to the original game). Create the same pixelated logo as the original game with the new game. See original intro screen: https://i.ytimg.com/vi/7IoD7YnnI-c/hq720.jpg 

9th

add a matching 8 bit music track.

10th

The music is horrible; make the tune more interesting. Added drums or similar. Maybe use a library like Band.js?
