# Noughts_and_Crosses

## Game Rules

- There are two players in the game (X and O)
- Players take turns until the game is over
- A player can claim a field if it is not already taken
- A turn ends when a player claims a field

- A player wins if they claim all the fields in a row, column or diagonal
- A game is over if a player wins
- A game is over when all fields are taken

### Victory Conditions
'≡' 3 horizontal possibilities  
'|||' 3 vertical possibilities  
'X' 2 diagonal possibilities  

## User Stories

```
As player1
I want to be able to enter an 'X' into any of the 9 possible spaces.

As player2
so i can play
I want player1's turn to end.

As player2
I want to be able to enter an 'O' into any of the 9 possible fields.

As a player
I should not be able to pick a field that is already claimed.

as a player
I want the game to tell me i have won if i get three in a row.

as a player
I want the game to end in a draw if all fields are taken.
```

## Class Diagram (UML)
### Objects:
- Player
- Game

### Messages:
- move(field)
- endTurn
- isValidMove
- isWinner
- isDraw
- isGameOver

### Data storage

1 | 2 | 3  
--|---|--  
4 | 5 | 6     
7 | 8 | 9   

fields = [1, 2, 3, 4, 5, 6, 7, 8, 9]
