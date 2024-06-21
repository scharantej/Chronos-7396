## Flask Application Design for a Mobile Endless Level-Based Game

### HTML Files

- **index.html:** This will be the main HTML file for the game. It will include the game's main screen with the start button, level selection, and other necessary elements.
- **game.html:** This HTML file will display the actual game. It will include the game board, player character, enemies, and other game elements.
- **level_select.html:** This HTML file will display the level selection screen. It will contain a list of available levels to choose from.

### Routes

- **homepage()**: This route will handle the main game page, which will include the game's main screen and level selection.
- **start_game()**: This route will initiate the game by setting up the game board and player character.
- **play_game()**: This route will handle the actual gameplay, including player movement, enemy AI, and level progression.
- **select_level()**: This route will allow players to select a level to play.
- **game_over()**: This route will handle the end of the game, displaying a game over message and providing an option to restart the game.