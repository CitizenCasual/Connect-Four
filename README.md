# Unit 1 Project Planning Materials

## Connect 4 wireframe:
![Connect 4 WireFrame](https://i.imgur.com/AX882Qx.png)

## Pseudocode:

- [ ] Define all winning combos in a constant

- [ ] Define variables that track the game ex. whose turn it is, the array to represent the board, if either player has won, and game info

- [ ] Create cached elements for each bubble, the messages that are displayed on the page, the information box, and the play/reset button

- [ ] Create event listeners for bubble clicks, play and reset button clicks, and info button clicks to update style

- [ ] When the game opens, it should assign values to the state variables with a init function, and listen for user input (player clicking a bubble)

- [ ] render function to assign styles to bubbles when clicked and takes all cached elements into DOM 

- [ ] click function to bring up reset button, check if bubble is taken(if not, assign value of turn to array index), checks for winner, switches player turn, calls render to update style, update message to show whose turn it is or who won if win is true

- [ ] check winner function to see if any winning array has been met, assigns win to whoever won, updates message to congratulate, and updates game info

- [ ] update winner function to take winning info, update total games played and player wins

- [ ] game info will include games played and number of games won by each player

- [ ] replay function that resets the game to initial load state

- [ ] The info button, when clicked, should show how many games were played, and how many games each player won. These values will be updated with each game. Creates pop up screen with game data. (light/dark mode?)


