# Tic-Tac-Toe Game

## Description:
The "Tic-Tac-Toe Game" project is an implementation of the traditional Tic-Tac-Toe game in Python, designed to provide an engaging and interactive gaming experience. This project comprises a series of well-structured functions that collectively allow two players to engage in a game of Tic-Tac-Toe. The project's primary goal is to offer an engaging and entertaining platform for users to play the classic game, following the fundamental rules and mechanics associated with Tic-Tac-Toe.
Each player chooses between X and O and the first player starts to draw the X on the space on the grid followed alternatively by the other until a player successfully marks a streak on the grid else if all spaces are filled the game is set to draw.

## Key Features:
1. **Displaying the Game Board:** The project begins by creating a game board, represented as a list of spaces, with each index corresponding to a number on a number pad. The `display_board` function presents the current state of the game board with updated marker placements after each turn.

2. **Player Input and Marker Assignment:** The `player_input` function ensures that players can choose their markers, 'X' or 'O.' It incorporates input validation, prompting players until they enter a valid marker choice. Once chosen, players are assigned their respective markers, with 'X' always going first.

3. **Placing Markers on the Board:** The `place_marker` function allows players to make their moves by specifying the desired position (from 1 to 9) on the game board. It places their marker on the chosen position and updates the board accordingly.

4. **Winning Condition Check:** The game checks for a winning condition using the `win_check` function. It examines all possible combinations of markers on the board to determine if any player has won. When a win is detected, the game congratulates the winning player and ends.

5. **Random Player Selection:** The project incorporates randomness through the `choose_first` function, which randomly selects the starting player. This adds an element of unpredictability to the game, making it fair and exciting for both participants.

6. **Checking for Available Spaces:** To prevent overwriting markers, the `space_check` function verifies if a specific board position is available for placement. This ensures that players can only select unoccupied spaces.

7. **Determining a Full Board:** The `full_board_check` function evaluates if the game board is full. If no player wins and all spaces are occupied, the game is declared a tie.

8. **Game Loop and Replay:** The main game loop allows players to take turns, continuously checking for wins, ties, and available moves. Once the game concludes, players are prompted to start a new game or exit the program, enhancing the overall user experience.

This project not only offers an opportunity to practice programming skills but also presents a fun and interactive game that users can enjoy with friends or against the computer. By following the rules and principles of Tic-Tac-Toe, this project provides an excellent way to explore Python functions, conditionals, loops, and user interaction while experiencing the thrill of the classic game.
