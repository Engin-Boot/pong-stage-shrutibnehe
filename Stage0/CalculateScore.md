# Player Details

## Feature

This module will calculate score

## Acceptance Criteria

### Scenario: Increment score of player

Given player is playing game  
When "Paddle Ball Collision" with player no is returned from 'collision check' module    
Then increment the score of the player by 1

### Scenario: Maximum play time reached

Given maximum play time of the game
When maximun time has reached  
Then call 'Declare winner module'
