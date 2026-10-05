# Snowman-Game-CSP2-Colab
A command line Hangman recreation game with a hint system, 2 difficulty levels, a bonus round, a points system, and a share card.

My Special Features for This Project:
 - A bonus round. If the user guesses the first correctly, they can choose if they want to do another round.
 - A points system. Points are calculated with a simple equation based on how many guesses and lives are left when the user finishes the round.
 - A share card. The share card is a short line that shows the score, the word they guessed, and in how many guesses. This share card challenges friends to compete and beat their score.

How it Works:
 - When the user selects their difficulty, the game chooses a random word from a normal or difficult word bank using .rand.
 - After a guess, the game checks every single letter of the word with a "for i in range" loop and replaces every corresponding letter in the displayed hidden word.
 - When the user asks for a hint, the game replaces the first two hidden letters of the word with the first two letters of the answer.
 - If the user guesses the final word correctly while having at least one guess and one life left, they win. If they can't do that, they lose.

Challenges:
My biggest challenge throughout this project was figuring out a way to check every single letter of the answer, then replacing the corresponding index number of the hidden word with the letter from the answer. This took a lot of trial and error, but it eventually worked, which was a very satisfying achievement for me.

What I'd Improve With More Time:
I have not yet learned how effectively use a display, so if I could, I would add a front-end display.

Made by Graham Greenberg ——  https://github.com/ggreenbe 

