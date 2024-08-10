# Hangman

Hangman is a single-player game where the player has a finite number of guesses to try
and guess all the letters that make up a secret word. After printing an introductory message
explaining the game to the player, the computer selects a secret word at random. Then the
player does a series of turns. In each turn, the player guesses a letter from A-Z. Incorrect
guesses are displayed as an evolving picture of the player being hanged at a gallows. For
each incorrect guess, a new part of a stick figure—first the head, then the body, then each
arm, each leg, and finally each foot—is added until hanging is complete.
On each turn, the program shows a hint about the secret word. The hint is initially a row
of dashes, one for each letter in the secret word. For example, if the secret word is
"HELLO", the hint is "-----". If the player's guess is a letter that appears in the secret
word, the hint is updated so that all instances of that letter are shown in their correct
positions. For example, if the secret word is "SHELLS" and the player guesses "H", the
hint becomes "-H----". If the player then guesses "L", the hint becomes "-H-LL-".
