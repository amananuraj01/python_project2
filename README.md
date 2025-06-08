# python_project2
Mega Project - (Water-Snake-Gun) GAME

This Python program is a fun and interactive version of the classic “Water-Snake-Gun” game, which is a variation of **Rock-Paper-Scissors**.

 🧠 How the Game Works:

* The player enters a choice:

  * `s` for "Snake" 🐍
  * `w` for "Water" 💧
  * `g` for "Gun" 🔫
* The computer randomly selects one of the three options.
* The winner is decided based on the following rules:

  * Snake drinks Water → Snake wins
  * Water douses Gun → Water wins
  * Gun shoots Snake → Gun wins
* If both player and computer choose the same, it's a "draw".

 💻 What the Program Does:

* Uses the `random` module to let the computer choose a random option.
* Accepts user input (`s`, `w`, or `g`) and maps it to the corresponding choice.
* Displays both the user's and computer's choices in full text.
* Determines and prints whether the user **wins, loses, or draws** the game.

 🔧 Key Python Concepts Used:

* `random.choice()` for random selection.
* Dictionaries for mapping short inputs to readable game choices.
* Conditional statements (`if-elif-else`) for decision making.
