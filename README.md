# CS-32-Final-Project
Alex Baker, Cameron Snowden, and David Hill



Project Goal:
Create a version of Texas Holdem in which a player plays against some number (random or chosen) of computer players and maybe even other people, depending on the difficulty of the overall task.

Subtasks to Accomplish:
Create a deck using some data structure (maybe with dealt cards visually displayed via ASCII)
Need suit hierarchy too (spades = $, hearts = @, clubs = &, diamonds = ^ maybe)

Reshuffle each hand or instead of choosing index 1,2,3…. We could choose a random index each time and “remove” the card from future choices

Reset all bets, hole cards, and community cards after a hand, options for players/computers to walk away with their earnings

Track current player and computer hands (hole cards) using another data structure

Pull cards from the deck to player and computer hands
(maybe specific named hands like flush, royal flush, straight, 4 or 3 of a kind, full house, etc)

Maybe use named hands in a list for computers to check their hands against and then some way of evaluating hands that aren’t in that list (a list with all possible hands would take a long time for the computer to check against and a long time to hard code)

Handle community cards using something similar to the data structure used to handle player and computer hands

Pull cards from the deck to the community card list

Computers will need to check their hands against the cards in the community card list to evaluate their hands

Computer bluffs
Work out a way for the computer to decide whether or not a bluff is appropriate if it has a bad hand (game could be somewhat predictable against computers that were only capable of mathematically making the best choices)

Handle computer and player bets; have the player and each computer start with the same amount of chips

Implement big and little blinds (easy)

Using a solution similar to the computer bluffs task above, have computers decide to call, raise, or fold based on the evaluation of their hands
Computers should play with the goal of maximizing their chip counts, so they should make decisions to call, raise, fold based on the quality of their hand (what they can do) and what cards they know are out of the deck (their hole + community cards; what other players can do)
At any betting point/after any flop player/computers may “fold” and stop playing the hand, if only one player remains then the hand ends and he takes the pot

Need to work out the separate pots for if a player goes all in early in the round against players with more chips who continue betting
This will be a larger, difficult step

Overall, managing data structures (hands, decks, cards, etc.) will be the first big task, determining winners comes next, followed by betting, and lastly interconnected computers for multiple/separate device players and a computer player.




***STATUS UPDATE***
We have doubled down on this idea and begun implementing some of the steps above. 
We have begun with setting up a deck, hands, and preliminary functions.

Our primary concern at the moment is to accomplish all of the separatre tasks of the game but not to put them together to reate one full game or round yet. 

We currently have the initial dealing functions and structures set up. We might begin adapting the code for the initial deal to also run the flop (frist three community cards), the turn (fourth), the river (fifth), but betting is a much more complex process, especially for the computer players. We'll be in office hours to ask about this, other structures we need to include, and what other functions we could develop now.

Currently, the player can input the number of players to play against and the automated dealer reacts by dealing that number of hands.



***FINAL SUBMISSION***


