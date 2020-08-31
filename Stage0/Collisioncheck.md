# Collision Check

## Feature

This module will check the type of collision

## Acceptance Criteria

### Scenario: Collision of Ball with Paddle

Given player is playing game  
When ball hits paddle of player 1 or player 2  
Then return "Paddle Ball Collision" with player no
to 'Score Calculator' module
and 'Update Ball Direction' module

### Scenario: Collision of Ball with walls

Given player is playing game  
When ball hits the walls  
Then return "Ball Wall Collision"
to 'Update Ball Direction' module
