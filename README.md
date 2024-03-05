# Capstone
Chess game

##Synopsis
This project is a simple chess game that has visuals for game turns, results, etc. It also implements different illegal moves, and features to chess, such as En Passant and Promotion.

## Motivation
I wanted to find something to make that would help me on my journey in learning about game development.

## How to run
Open the file, go to the src, make sure all the classes are together, and click run.

## Code Example

private boolean kingCanMove(Piece king) {
		
		 if(isValidMove(king, -1,-1)) {return true;}
		 if(isValidMove(king, 0,-1)) {return true;} 
		 if(isValidMove(king, 1,-1)) {return true;}
		 if(isValidMove(king, -1,0)) {return true;}
		 if(isValidMove(king, 1,0)) {return true;}
		 if(isValidMove(king, -1,1)) {return true;}
		 if(isValidMove(king, 0,-1)) {return true;}
		 if(isValidMove(king, 1,1)) {return true;}
		 
		 return false;

This line of code represents the different degrees/spots the king can move on the board, in all directions.If the king can move to any of these spots, it returns true. Otherwise, returns false, and the game shows that through a gray square where the king is trying to move. 

## Test

1. Download the file
2. Extract it
3. Find the src file, the main, and piece files
4. Add them all together and run/edit the code however you like

## Contributors
Contributors to this project were a RyiSnow and Screen Works
   
