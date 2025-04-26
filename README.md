# -2--SpringHackathon2025
Our Game
-------------------------------------------------------------------------------------------------------------------------------------
The player controls a car PNG moving side-to-side between 5 lanes. Other cars (obstacles) randomly spawn at the top and move downward 
— if you crash into one, bad things happen (pay money, take damage). Car parts (engine, tires, battery, etc.) 
randomly spawn in lanes too. Picking up parts = you "fix" parts of your car.
-------------------------------------------------------------------------------------------------------------------------------------
Event               | Effect
--------------------|----------------------------------------------------------------------------------------------------------------
Pickup correct part | +Fix part, +speed
Pickup wrong part   | (Maybe) no penalty??
Miss correct part   | -Stay broken, drive slower
Crash into car      | -Lose money or part
Run out money/speed | -Lose game
Full repair done    | -Win the game

Visual Layout
-------------------------------------------------------------------------------------------------------------------------------------
Top-down view.
- 5 vertical lanes across the screen.
- Player's car can shift left/right or up/down with arrow keys.
- Other cars and parts will be in the path you're driving.

Rules
-------------------------------------------------------------------------------------------------------------------------------------
Pickup parts to fix your broken car parts.
- Miss a needed part? Your car stays broken → you drive slower → higher risk of crashing.
- Crash into other cars? You slow down
- Break down completely (if you go too slow or take too much damage)? Game Over or pay.
- Win Condition: Fully fix your car (all parts replaced) and survive to the finish line.
- Starting Cash: ex $500
- Car Health: some parts are broken at the start.
- Speed: slower if the car is damaged, faster when repaired.
- Inventory: parts you've collected.
-------------------------------------------------------------------------------------------------------------------------------------
