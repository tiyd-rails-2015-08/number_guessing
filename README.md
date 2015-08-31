# Number Guessing Game

## Description

Create a number guessing game in which the computer picks a number and you have to guess it.  The computer will give you cues like 'Too High' or 'Too Low.'

## Objectives

After completing this assignment, you should...

* Understand what methods are and how they can be used to:
  * Reduce code repetition
  * Improve readers' ability to reason about code
* Understand how ruby code resides on the file system and how it is executed
* Be able to use puts and gets
* Be able to add, commit, and push to github
* Create, add to, and check for presence in an array

## Deliverables

* **A GitHub repository.**
* **A Ruby file called `guessing_game.rb`.**
* **A series of commits on that repository.** After you get each requirement working, run `git add .`, then `git commit -m "TEXT HERE"`, where TEXT HERE should be replaced with the description of the requirement you just finished.

After your work is complete, make sure to `git push` your changes up to GitHub.  Feel free to do this more than once along the way, of course.

Use the homework submission form on the course website to turn in a link to your GitHub repository.

## Normal Mode

Your goal for tonight is to create a number guessing game. Your program should pick a random number between 1 and 100 and ask you for a guess. If your guess is less than the program's number, it should tell you that you were low and let you guess again. If the guess is greater than the program's number, it should tell you that you were high and let you guess again. If your guess is correct, the program should tell you that you win and then quit.

Other requirements:

* After 5 incorrect guesses, the program should tell you that you lose.
* If you guess the same number twice, the program should ask you if you're feeling all right (or something similarly sarcastic).
* Your code should include at least two methods.
* This game should be run from the command line by typing "ruby guessing_game.rb".

## Hard Mode

Hard Mode has two parts to it:

1. In normal mode, you will probably use the "rand" method. In hard mode, find another way!
2. The program should also comment on your behavior if you make a guess that doesn't help you.  For example, you might say "50" and then be told "that's too low."  If you then guess "25," you're just wasting a guess.

## Nightmare Mode

Write the opposite program as well: you, the user, pick a number between 1 and 100. The computer has to guess the number. You tell it whether it's too high, too low, or correct after each guess. The computer gets five guesses. The computer should tell you if you are lying to it.  (e.g. Computer guesses 50, you say "High."  Computer then guesses 49 and you say "Low."  You'd be lying, as there are no numbers between them.)

## Additional Resources

If you do Nightmare Mode, you might want to:

* [Watch this video](https://www.youtube.com/watch?v=JQhciTuD3E8) about binary search
* [Read this article](http://en.wikipedia.org/wiki/Binary_search_algorithm) about binary search
