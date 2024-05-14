# MasterMind
Code inspired by the famous MasterMind Game


This project is a Java implementation of the classic Mastermind game. Mastermind is a code-breaking game for two players. One player, the codemaker, chooses a sequence of colors, and the other player, the codebreaker, tries to guess the sequence within a certain number of attempts. This version of the game generates a random sequence of colors that the player must guess.

Features
Random Color Generation: The system generates a random sequence of four colors from a predefined set.
User Input: The player can input their guesses via the console.
Feedback System: After each guess, the system provides feedback on the correctness of the guess.
Limited Attempts: The player has up to 12 attempts to guess the correct sequence.
Custom Data Structures: The game utilizes custom implementations of positional lists to manage guesses and feedback.
Rules
The system randomly generates a sequence of four colors.
The player attempts to guess the sequence by entering four colors.
After each guess, the system provides feedback:
"x" indicates a correct color in the correct position.
"o" indicates a correct color in the wrong position.
"-" indicates an incorrect color.
The player wins if they guess the correct sequence within 12 attempts.
The game ends if the player exhausts all attempts without guessing the correct sequence.
Technologies Used
Java
Custom data structures: Positional lists
Classes and Interfaces
Main Classes
Game: The main class that initializes and runs the game.
Peg: Represents a peg with a specific color.
Interfaces
List<E>: A simplified version of the java.util.List interface.
Position<E>: Represents a position in the list, storing an element and its index.
PositionalList<E>: Represents a list with positional access methods.
Data Structure Implementations
LinkedPositionalList<E>: A doubly linked list implementation of the PositionalList interface.

How to Run
Clone the repository:

Compile the Java files:

Run the game:

Follow the prompts to guess the sequence of colors.

Example Gameplay

Secret code generated. Try to guess the colors!
System:		Guess # 1:
Player:		red blue green yellow
System:		x - o -
System:		Guess # 2:
Player:		red yellow blue green
System:		x x - o
System:		Guess # 3:
Player:		red yellow green blue
System:		x x x x
You cracked the code!

Emhenya Supreme
Based on "Data Structures and Algorithms in Java, Sixth Edition" by Goodrich et al.
