# Declare Winner

## Feature

This module will declare winner.
After declaring it will prompt user to restart or quit game

## Acceptance Criteria

### Scenario: Player 1 is winner

Given players are playing game  
When declare winner module called  
Then if player 1 score is greater than player 2,
declare player 1 winner

### Scenario: Player 2 is winner

Given players are playing game  
When declare winner module called  
Then if player 2 score is greater than player 1,
declare player 2 winner

### Scenario: Scores are equal

Given players are playing game  
When scores of both players are equal  
Then the game is started again

### Scenario: Restart game

Given winner is declared  
When player clicks on play again game  
Then game is started again

### Scenario: Quit Game

Given winner is declared  
When player clicks on quit game  
Then game is over
