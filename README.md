
# Code-Me_Python_Hackaton1

### About this repo

This is a repo that was created during the first hackaton.
From the list of given tasks at least one task (of my choice) had to be implemented, described and delivered.

**List of tasks:**

- Hangman ---> (chosen task)
- Address book
- RPG Warrior's name generator
- RPG History (driven by user's choice)
- Card game (war)
- Quiz
- Tic tac toe game

## Hangman

### Table of contents
* [Introduction](#introduction)
* [Project status](#project status)
* [Technologies](#technologies)
* [Solution concept](#solution concept)
* [Requirements](#requirements)
* [Run the program](#run the program)
* [Usage](#usage)
* [Sources](#sources)

### Introduction

Hangman is a guessing game for two or more players. One player thinks of a word, phrase or sentence and the other(s) tries to guess it by suggesting letters within a certain number of guesses. Originally a Paper-and-pencil game, there are now electronic versions.

This is an implementation of this game, a console application version.
Computer has thought a word. At the beginning of the program, only the hidden word length is given to the user. User has to guess the computer's hidden word by providing single letters (one at a time, in a specific number of attemps) or the whole word at once.

The number of attempts for user to guess (either a single letter or the whole word) equals the length of computer's hidden word to guess. Seems fair, right?

### Project status

Implementation finished. Will not be further developed or supported.

### Technologies

The program is implemented in pure Python. No complications.

### Solution concept

In the implementation following were used:

- if statements and for loops
- lists
- string methods
- formatted string literal (f-string)

### Requirements

To run the program you only need to install Python 3 (any version). You can get Python from the following: http://python.org/download/. Simply download the Python installer and follow the instructions.

### Run the program

Open a command-line and type in the word 'python3', followed by the path to your script, just like this: <br>
>$ python3 hangman.py

If everything works okay, after you press 'Enter', you'll be provided with the short info needed to start the game and then asked to give an input.

### Usage

User can type correctly:

- single letter (alphabet):
<br>If user guess is right, then all the guessed letters are shown after every attempt.


- word(s):
<br>If user guess is right, then user wins and the program will end.


- 'exit' (to quit the program):
<br>The program will quit with exit code 0.

### Sources

This program is implemented for the hackaton. The requirements for this task (in polish) are defined here: 

>github.com/ritaly/pycodeme22 - [Propozycje zadań warsztatowych](https://github.com/ritaly/pycodeme22/blob/main/hackaton_1/README.md)
<br>('Wisielec' heading)

Documentation that helped during implementation:
- docs.python.org - [Built-in Types](https://docs.python.org/3/library/stdtypes.html#string-methods)
- docs.python.org - [5. Data Structures](https://docs.python.org/3/tutorial/datastructures.html#more-on-lists)
- docs.python.org - [7. Input and Output](https://docs.python.org/3.7/tutorial/inputoutput.html#fancier-output-formatting)

All the code is 100% original, individual work.

### About the author

I'm a regular manual tester with almost 3 years of experience.<br>
I like to take a ride on my bike, have a race with a go-kart sometime, I also like travelling. I have a 5 years old ragdoll cat, his name is Idris :).<br>
I wish to be a Python developer, machine learning and AI is my goal.<br>
You can find more info about me on my LinkedIn profile [here](https://www.linkedin.com/in/daniel-matkowski/).<br>
If you have any questions or you just find my repo interesting, you're welcome to contact me in LinkedIn chat.