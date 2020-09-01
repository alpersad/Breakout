# Breakout Java

A breakout game designed and built in Java for a user interface course.
![Breakout Game](https://github.com/alpersad/Breakout/blob/master/docs/screenshots/normalgame.png)

## Design

Model, View, Controller (MVC) is the basic principle behind this game's design.
The Model aspect handles all logic concerning ball position, ball direction, paddle position, brick position and status, etc.
The View and Controller aspects are coupled together in the main interface. The display of the game serves as both
the View of the Model and Controller for the user's input.

## Features Implemented

### Scalability

The game is fully scalable to any size. All the elements in the display scales proportional to the display window.

### Sticky Ball (Bonus)

In addition to the base Breakout game, I added an additional game element named sticky ball.
When a player has obtained enough points in the game, the player can activate the "sticky ball" mode which
attaches the ball to the paddle on next contact. This allows players to reposition and launch the ball.
![Sticky Ball Feature](https://github.com/alpersad/Breakout/blob/master/docs/screenshots/stickyon.png)

## How to Play

Download and run the Breakout.jar file.

![Instructions](https://github.com/alpersad/Breakout/blob/master/docs/screenshots/instruction_page.png)
