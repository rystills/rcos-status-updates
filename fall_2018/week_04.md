## Last Week's Accomplishments
Last week, I implemented path drawing with collision detection. Drawing paths is the user's main interface with the game, as it enables the user to tell a unit where to go and what to go. As such, it's important that path drawing work as smoothly and consistently as possible. By using circlecasts, I was able to grant the paths precise collision detection, ensuring that paths cannot pass through solid walls or objects.

## This Week's Plan
This week, I intend to make units move on the path. As path drawing deals with collisions, units themselves will not need to worry about colliding with static geometry, but they will need to ensure that they move at a framerate independent speed, and that their rotation remains sync'd up with their effective facing direction. Additionally, there are a few collision bugs / corner cases in path drawing that I'd like to smooth out this week.

## Anything Blocking?
No blocking factors this week.

## Notes
N/A
