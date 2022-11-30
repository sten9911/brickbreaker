# make-your-game
This is the first JS project in the curriculum, I have chosen to recreate Brick Breaker because I had a lot of fond memories from childhood playing this game. The game has to run at 60fps at all times (or 120 I guess).

# Description
* The goal of this game is to break all the bricks with a ball in a particular level.
* The player has 3 lives. Each time the ball touches the bottom of the screen and is not bounced back by the paddle, a life is substracted. When all 3 lives are gone, the players loses. 
* However if all the bricks are broken, the player wins. 
* Occasionaly when a brick is broken, the player also gets some useful bonuses. The only bonus I have implemented in my project, is an additional ball.
* Some of the bricks are stronger than others, and need 2 collisions to break down.

# Running the project
To run the project, you have to start the website up in your local server.
The easiest ways to do that would be to use :
* Live Server extension in you code editor
* If you have python installed
> python -m http.server
* If you have node.js installed, use npm scripts or just
> node server.js

# How to play
* Control the paddle with **LEFT AND RIGHT ARROW KEYS**.
* Shoot the ball with **SPACEBAR**.
* To pause the game press **ESCAPE**. Same to unpause or just click Resume.
* To restart your game, go to the pause menu and press Restart.

# Creators: Sten Orasmäe