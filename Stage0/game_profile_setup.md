# Game Profile Setup

## Feature

This module helps to sign up for a new profile in the game or to sign in

## Acceptance Criteria

### Scenario: Sign Up the new User

  Given the pong game is installed on the device

  When a new user launches the game for first time

  Then he/she is asked to create a new profile and perform sign up process

### Scenario: Start an old game or Resume a previous game

  Given the pong game is installed on the device and user is signed in

  When a old user launches the game

  Then he/she can start an old game or previous game
  
### Scenario: Edit the profile settings

  Given the pong game is installed on the device and user is signed in

  When a user clicks on change profile data

  Then he/she can edit his/her profile data and save it in the game
