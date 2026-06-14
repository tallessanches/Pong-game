# Pong Game

Fictional Pong Game project developed with JavaScript.

| Name | **Pong Game** |
|------|------|
| Technologies | JavaScript |
| URL | https://editor.p5js.org/tallessanches/full/_Z_IgFMkZ |

<!-- Insert image with #vitrinedev at the end of the link -->
![](https://raw.githubusercontent.com/tallessanches/jogopong/main/jogopong.png)

## Project Details

- Changed the background color from gray to black by modifying the `background()` function parameter from `220` to `0`.
- Created the game ball using the `circle()` function.
- Implemented ball collision detection with the screen borders by checking its `x` and `y` positions.
- Improved code organization by adding comments and creating functions without changing the game's behavior.
- Created a function to draw the paddle.
- Enabled paddle movement using the keyboard arrow keys through `keyIsDown(UP_ARROW)` and `keyIsDown(DOWN_ARROW)`.
- Implemented collision detection between the ball and the player's paddle by checking their respective `x` and `y` positions.
- Imported a GitHub library to handle collision detection.
- Reused the `showPaddle()` function to create both the player's paddle and the opponent's paddle.
- Reused the `checkPaddleCollision()` function to detect collisions with both paddles.
- Added a scoreboard to track the player's and the opponent's points.
- Customized the scoreboard by adjusting its size.
- Added sound effects to improve the overall gameplay experience and immersion.
