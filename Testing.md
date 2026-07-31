# Alien Evasion Testing 

## Test plan 
The table below summarises the expected functional testing to be carried out during the development of **Alien Evasion**.

| Test No | Test Description | Expected Result | Status |
|:-------:|------------------|-----------------|:------:|
| 1 | Test gravity applied to UFO character | UFO falls downwards. | ✅ Pass |
| 2 | Test character movement (Space key press) | UFO bounces upwards on each key press. | ✅ Pass |
| 3 | Test collision between character and top alien | Game Over screen is displayed. | ✅ Pass |
| 4 | Test collision between character and bottom alien | Game Over screen is displayed. | ✅ Pass |
| 5 | Test collision with the top of the game window (ceiling) | Game Over screen is displayed. | ✅ Pass |
| 6 | Test collision between character and bottom of game window | Game Over screen is displayed. | ✅ Pass |
| 7 | Test score increment | Score increases by one every second while the game is running. | ✅ Pass |
| 8 | UFO animation points upwards | When the Space key is pressed, the UFO tilts upwards slightly. | ✅ Pass |
| 9 | Welcome sound test | Welcome sound plays when the game launches. | ✅ Pass |
| 10 | Collision sound test | Explosion sound plays when a collision occurs. | ✅ Pass |
| 11 | Space key pressed on Start screen | Game starts and continues to the gameplay screen. | ✅ Pass |
| 12 | Space key pressed on Game Over screen | Game restarts and returns to the gameplay screen. | ✅ Pass |
| 13 | Start screen game launch | Start screen appears when the game launches. | ✅ Pass |
| 14 | Alien height during gameplay | Aliens spawn at different heights chosen randomly from a predefined list. | ✅ Pass |
| 15 | Alien gap during gameplay | Gap between alien pairs is selected randomly from the available values. | ✅ Pass |
| 16 | Random UFO selection | One of four UFO sprites is selected randomly each time a new game starts. | ✅ Pass |
| 17 | UFO animation points downwards | When the Space key is not being pressed, the UFO points downwards. | ✅ Pass |
| 18 | Game Over collision test | Game Over screen is displayed after a collision. | ✅ Pass |
