Dice Game Project
This project contains a simple console-based dice game where players take turns rolling a dice and moving their positions based on the roll. The game continues until a player reaches the maximum length or the game is manually ended.

Files and Classes
Program.cs
The entry point of the application. It prompts the user to enter the number of players and the maximum length of the game, then starts the game.

LessThanZeroException.cs
A custom exception class that represents an error when a player's position is less than zero.

GreaterThanMaxPossibleException.cs
A custom exception class that represents an error when a player's position exceeds the maximum length of the game.

IPlayer.cs
An interface that defines the contract for a player in the game, including methods to roll a dice and display the player's name.

Player.cs
A class that implements the IPlayer interface and represents a player in the game. It includes methods for rolling a dice, moving positions, and displaying player information.

Game.cs
The core class that handles the game logic. It manages the players, the game loop, and determines the winner of the game.

How to Run
Clone the repository to your local machine.
Navigate to the directory containing the Program.cs file.
Compile the program using a C# compiler or open it in an IDE like Visual Studio.
Run the compiled executable or start the program from the IDE.
Game Rules
Players take turns rolling a dice.
If a player rolls a 5, they move back 5 positions. Otherwise, they move forward by the number rolled.
If a player lands on the same position as another player, the other player's position is reset to zero.
The game ends when a player reaches or exceeds the maximum length or when the game is manually ended by entering 'e' or 'exit'.
Note
This is a simple console application and does not include a graphical user interface. All interactions with the game are done through the console.
