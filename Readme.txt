Professional skills game plan

Bobs Gun

Shoot in all directions (2 versions of laser, updown and leftright. Lasers are stored below the player
and y position is changed when space is pressed. Movement of laser will depend on player wall state
in which direction the laser will fire in). Laser could have a fire state ( fired or not fired)

Bullet collision with enemies

Enemies death. When enemies are shot, currently they will have 1 health point. So instant collision
with the laser will result in death. Death animation will be particle explosion. Enemy quad will be
moved off-screen.

Player health

Player will have a certain number of hearts as health instead of a health bar. Player starts with 10
hearts, each time he collides with an enemy the player could:

 freeze for 2 seconds and loose 1 health.
 Bounce back from the enemy and loose 1 health.

Experiment with both to see which is best.

Score

Will start at 0.
Enemy death 10 points
Key collection 2 points
Door unlock 5 points
Book collection 5 points
Health collection 5 points per heart collected

Enemy class

Polish of enemy class, turning them into pointers.

Sprite skins

Find more sprite skins for enemies, modify current sprites so they can be implemented.

Level 1 finish

All books collected, exit gateway needs to open and player travels to portal to complete the level.

Level editor

Outputting to all base model positions to output text file.

Work on level 2
