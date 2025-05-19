# CodeAlpha-MEMORY-PUZZLE-GAME
The Memory Puzzle Game is a simple brain-training game where the player must match all pairs of hidden tiles before the countdown timer reaches zero.

🕹️ Gameplay:
The game displays a 4x4 grid of face-down tiles (16 tiles in total).

Each tile hides a number from 0 to 7, and each number appears exactly twice (forming 8 matching pairs).

Players click on tiles to reveal them:

If two consecutively clicked tiles show the same number, they remain revealed.

If the numbers do not match, both tiles are hidden again after a short delay.

The player must use memory and strategy to remember the positions of previously revealed numbers to make matches.

⏱️ Time Limit:
A 60-second timer starts when the game begins.

The player must match all pairs before the time runs out.

If the time runs out, the game ends with a "Time's up! You lost" message.

✅ Win Condition:
The game is won if all pairs are correctly matched before the timer reaches 0.

A victory message, "Congratulations! You won!" is displayed.

❌ Lose Condition:
If the player fails to match all pairs within the time limit, a message "Time’s up! You lost." is shown.

🎨 Visual Design:
Tiles are gray when hidden and blue when revealed.

A number is shown on each revealed tile.

The remaining time is displayed in red at the bottom of the screen.

🛠️ Technologies Used:
Python programming language

Pygame library for graphics, event handling, and GUI

💡 Purpose:
This game is useful for:

Improving memory and concentration

Demonstrating Pygame GUI development

Learning basic game mechanics and logic
