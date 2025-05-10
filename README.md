Install py game through command: 'pip install pygame'
Then run the project through: 'python main.py'

About the Game
This is an AI-driven Snake and Ladder game where snakes and ladders appear dynamically on the board instead of being fixed. The game offers three difficulty modes: Easy, Medium, and Hard, each adjusting the challenge level based on time limits and the number and size of snakes.
AI Algorithms Used:

Monte Carlo Simulation
This algorithm predicts the player’s possible future positions by running thousands of simulations before each move. Based on the resulting probability distribution:
Snakes are placed on the most likely cells the user might land on.
Ladders appear on less likely cells to reduce chances of rapid progress.

MiniMax Algorithm
This algorithm works to minimize the player’s progress toward cell 100. As the player approaches the goal, the AI increases the difficulty by placing more and larger snakes. The intensity of this behavior varies by difficulty mode.

Difficulty Modes:
Easy: Fewer and shorter snakes, more time to play.
Medium: Increased number and size of snakes, with less time.
Hard: Most snakes, largest in size, and minimal thinking time.

Objective:
Just like the traditional Snake and Ladder game, your goal is to reach cell 100. However, with dynamic obstacles and AI predictions, every move counts — and the snakes are much smarter now.

Enjoy the game!
