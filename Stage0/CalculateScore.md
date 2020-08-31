# Player Details

## Feature

This module will calculate score

## Acceptance Criteria

### Scenario: Increment score of player

Given player is playing game  
When paddle ball collision returned
with player no from collision checker
Then increment the score of the player by 1

### Scenario: Maximum play time reached

Given maximum play time of the game  
When maximum time has reached  
Then call 'Declare winner module'
