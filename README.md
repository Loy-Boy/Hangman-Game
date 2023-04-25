# Hangman
Hangman game for the WBS Coding School "Data Science" bootcamp.

Created by Frederik Loy, April 2023.

## IPython Notebook
Originally, this project was constructed in google colab. Hangman_final.ipynb is a copy of that notebook and useable with google colab. Execute all cells from top to `RUN`, to initiate the game.

## Set Up Difficulty / Possible Words
The `get_word()` function allows you to define the amount of words in the original word-pool.
Also there you can filter the Word pool for the amount of unique letters (the fewer, the harder).
And after the selection of the unique letters, you can filter by word-length.
This function will define the word, that will be used by the game. The word will only be changed, if you run this function again.

##Starting the actual Game:
The `game()` function will start the execution of the actual game.
After each round you will have to rerun the `get_word()` function again, to get a new word, before rerunning the `game()` - function
