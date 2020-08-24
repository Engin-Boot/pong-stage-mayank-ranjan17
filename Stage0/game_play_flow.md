# Game Play Flow Setup

## Feature

This module is used to play the game

## Acceptance Criteria

### Scenario: Choose the criteria of the game Multi Player or Single Player

  Given the user is signed in and starts a game

  When a user enters the game he/she choose the single player or multiplayer version

  Then he/she starts the game when the ball is served by either one of the user or the computer

### Scenario: The paddle movements in the game

  Given the pong game is in run state

  When a user receives a ball on his/her court side 

  Then he/she move the paddle in the y direction in order to avoid the ball from touching the wall
  
### Scenario: The ball movements in the game initiated by a user

  Given the pong game is in run state 

  When a user hits a ball with his/her paddle

  Then the ball is moved in the opposite direction and the x and y coordinates of the ball is changed
  
### Scenario: The ball movements in the game occured due to boundary

  Given the pong game is in run state 

  When the ball hits the boundary

  Then score of the user on the opposition side gets update by one.
  
### Scenario: The playing time is completed

  Given the pong game is in run state 

  When the limited time to complete the game is finished

  Then the user with more points will be declared as the winner and the score will be updated in the user profile.
  
### Scenario: Pause the game

  Given the pong game is in run state
  
  When a user click on pause game button

  Then the user pong game is paused and a resume button will appear on the screen.
  
### Scenario: Exit the game

  Given the pong game is completed and an exit pop up or start new game option is visible on the screen

  When a user click on exit game button

  Then the user exits the game.
