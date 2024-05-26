# Decision-Modelling-Mini-Project
Topic:- Dragon Cherry Fest Dragon Cherry Fest is a custom Pac-Man inspired game environment built using Python's gym library and pygame. The game features a dragon (Pac-Man) that collects cherries (food) while avoiding skeletons (enemies) on a 20x20 grid. The game includes sound effects and a simple scoring system with penalties.

Features:- *Grid-Based Environment: A 20x20 grid where the dragon moves around to collect cherries and avoid enemies. *Dynamic Enemy Movement: Enemies move randomly after every few steps, making the game challenging. *Scoring System: Players earn points by collecting cherries and incur penalties when caught by enemies. *Sound Effects: Cherry collection and enemy encounters are accompanied by sound effects. *Graphical User Interface: The game uses pygame to render the grid, the dragon, cherries, and enemies. It also displays the score and penalty bars. *End Game Conditions: The game ends after a maximum number of steps, and the player is notified whether they win, lose, or draw based on the score and penalty.

Download the Assets:- Place the following assets in the project directory:

*dragon.png *cherry.png *skeleton.png *cherry_sound.wav *dragon_hurt.mp3 *Hitman.mp3

Controls:- Arrow Keys: Move the dragon up, down, left, or right.

Objective:- Collect Cherries: Gain points by collecting cherries. Avoid Enemies: Avoid getting caught by skeletons to prevent penalty points.

End Game:- The game ends after a maximum number of steps. The final score and penalty points are displayed. The player is informed if they win, lose, or draw based on their performance.

Code Explanation:- Dragon_Cherry_Fest Class Initialization: Sets up the game environment, including the grid size, initial positions, and game attributes. Reset: Resets the game state for a new episode. Step: Updates the game state based on the player's actions and checks for collisions with food or enemies. Render: Draws the game state on the screen, including the grid, dragon, cherries, enemies, and score/penalty bars. Helper Methods: Includes methods for displaying the score bar and end game message.

Run Game Function:- Handles the game loop, processes user input, updates enemy movements, and renders the game state.

Contributing:- Contributions are welcome! Please fork the repository and submit a pull request with your changes. Ensure your code follows the existing style and structure.

Acknowledgements:- Thanks to the creators of gym and pygame for providing the libraries that made this project possible. The sound effects and images are sourced from free online resources.
