# Project Name
This is an exercise of implementing some features in unity in order to make the game BreakBricks juicer.
2025/3/2

## Implementation
**_Changing the colors and sprites_**: Instead of randomly assigning colors for the bricks, I changed their sprites with the sprites from the Kenny Brick Pack.

**_Squeeze and stretch_**: The ball will be squeezed and stretched a bit while hitting bricks, walls, and the paddle.

**_Shake the screen when something good happens_**: The screen shakes when the ball hits anything.

**_Add sound effects_**: sounds when game objects collide with each other.

**_Add music_**: Background music

**_Make the elements fall off the screen when they are hit_**: Bricks will fall and disappear when they are hit by the ball.

**_Add a comet trail to the ball_**: I implemented the comet trail for the ball. And I also make it longer. The comet will also get smaller over time.

**_Add eyes_**: Two small horror eyes on the paddle that will stare at the ball all the time

**_Add a background to the game_**: I got a Lego image for the background.

**_Add particles when an element is hit_**: This is the part where I spend most of the time. I played around with the particle system for a long time. I made the brick and paddle play with some particles when they collided with the ball. I made a particle prefab that would be instantiated whenever the ball was hitting anything. I want to make the instantiated particle prefab appear in the opposite direction with respect to the object that the ball hits. But I don't know why, the rotation of the ball isn't toward its moving direction. So I failed. The particle prefab will only appear in the default direction(pointing up). 

## References
 * [Kenny Brick Pack](https://kenney.nl/assets/brick-pack)
 * [Background Music](https://nebula-audio.itch.io/free-sf-electronic-music-pixel-perfect/comments)
 * [Puzzle Pack 2, provided by kenney.nl](https://kenney.nl/assets/puzzle-pack-2)
 * [League Gothic Typeface](https://www.theleagueofmoveabletype.com/league-gothic)
 * [Orbitron Typeface](https://www.theleagueofmoveabletype.com/orbitron)

## Future Development
To be continued...

## Created by
Franklin Pu
