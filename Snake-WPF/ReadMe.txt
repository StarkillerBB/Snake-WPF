# Snake WPF Project
##### Author: Benjamin Lank
#### Description:
##### Snake application made in WPF with user controls and highscore.

#### Navigation menu:
ChangeLog:  
- [Version 1.1](#Version-1.1).  
- [Version 1.0](#Version-1.0).  
- [Version 0.3](#Version-0.3).  
- [Version 0.2](#Version-0.2).  
- [Version 0.1](#Version-0.1).


## Console menu.
### Short description of the menu and each method associated with it.

	1. DrawGameArea()
		* Draws and displays the gameboard.
	2. DrawSnake()
		* Draws and displays the snake onto the board.
	3. MoveSnake()
		* Moves the snake on the board.
		* Removes last part of the snake and inserts a new in front.
	4. StartNewGame()
		* Starts a new game with the default values.
	5. GetNextFoodPosition()
		* Calculates the next position for the next food.
	6. DrawSnakeFood()
		* Displays the food in the calculated position from the GetNextFoodPosition method.
  	7. DoCollisionCheck()
		* Checks if the head collides anything on the bord.
			*Snake head can collide with apple, another snake part and the edge of the board.
	8. EatSnakeFood()
		* Increase the length of the snake.
		* Removes the food located on the board.
	9. UpdateGameStatus()
		* Updates the score.
		* Updates the speed.
	10. EndGame()
		* Stops the game.
		* Checks if it's a new highscore.
	11. LoadHighscoreList()
		* Checks if the highscore file exists.
		* Loads the highscore file into a list and displays it.
	12. SaveHighscoreList()
		* Saves the list into the file, if the file exists overwrite the file with new information.


## ChangeLog.
### All changes will be added to this section.

###### 11/8/21
#### Version 1.1

###### Highscore list to the game, saving into file.

##### Added.

	* method that checks if it's a new highscore.
	* Highscores to a list, and saving the list into a file for future games.

##### Changed.

##### Removed.

---
###### 12/8/21
#### Version 1.0

###### User can now control the snake and pick up food to get a score.

##### Added.

	* user inputs to control the snake.
	* user can move around the window by simple drag&drop.

##### Changed.

##### Removed.

---
###### 12/8/21
#### Version 0.3

###### Added collisions for the snake.

##### Added.

	* Snake can now collide with the apple, causing the apple to disappear.
	* Snake can now collide with itself, causing a gameover.
	* Snake can now collide with the edge of the board, causing a gameover.

##### Changed.

##### Removed.

---
###### 6/9/21
#### Version 0.2

###### Food for the snake to collect to the game, new-game option.

##### Added.
	
	* Calculation to figure out where the next food position should be.
	* Displays the food onto the gameboard.
	* pressing space will start a new game with the default options.

##### Changed.

##### Removed.

---

###### 4/9/21
#### Version 0.1

###### Creates the board and snake for the game. 

#### Added.

	* method for creating the board.
	* method for creating the snake in the decided position.

##### Changed.

##### Removed.


