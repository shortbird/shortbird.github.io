# State Capitals Quizzes
Credit: [Al Sweigart in "Automate the Boring Stuff"](https://automatetheboringstuff.com/2e/chapter9/)

Say you’re a geography teacher with 35 students in your class and you want to give a pop quiz on US state capitals. Alas, your class has a few bad eggs in it, and you can’t trust the students not to cheat. You’d like to randomize the order of questions so that each quiz is unique, making it impossible for anyone to crib answers from anyone else. Of course, doing this by hand would be a lengthy and boring affair. Fortunately, you know some Python.

## Instructions
Write a Python program that:
* Creates 35 different quizzes
* Creates 50 multiple-choice questions for each quiz, in random order
* Provides the correct answer and three random wrong answers for each question, in random order
* Writes the quizzes to 35 text files
* Writes the answer keys to 35 text files

## Hints
* Store the states and their capitals in a dictionary
* Call ``open()``, ``write()``, and ``close()`` for the quiz and answer key text files
* Use ``random.shuffle()`` to randomize the order of the questions and multiple-choice options
* Follow along with the author of this project here (scroll down to the bottom where it says "Project: Generating Random Quiz Files")
  * https://automatetheboringstuff.com/2e/chapter9/
