# Chess
created by Nithin

A simple command line chess game using Python

## Starting the Game
1. Clone this repository
2. In the command line, go to the src directory
3. run `python chess.py` or `python3 chess.py`

## How to Play
The rules are standard chess rules.

Each turn, you will be prompted with `from: ` and `to: ` which you will enter a board position of a piece (ie. '2d') to where you want to move it (ie. '3d').

### Notes
Chess board only prints properly on Unix-type terminals due to system-specific colored printing. 
For Windows, check out Ubuntu on WSL.

Not currently supported: 
 * checking that king does not threaten king
 * checking for checks
 * checking for checkmates



##snapshot final output of the chess board game


![image](https://user-images.githubusercontent.com/83778315/189488842-a549578f-d181-4dec-afdc-a1e8d5300adf.png)



## approach for the problem statement
1. first i have taken the three attributes(inputs) chess,board,peice
2.so in chess code first i have taken that class named chess in that i have taken attributes like board turn and white ghost piece and black ghost peiceand 
also used the methods promote and move where promote do the action that promoting the pawn that has reached other side or another to the same piece
and i have also used some extra logic concepts like back tracking to make the moment of the pawn
3.and finally printing the board
4.and in the chess code also i have used the same back tracking logic for the target peice finding
and in the peice code specfically targeting the movements of the peice so here i have taken the functions like check_knight,check_diag_castle,check_diag,check_updown_castle,check_updown, and the peice class for the peice movements
5.so this the approach that i followed to develop the chess game for the two players with the rules mentioned in the problem statement
