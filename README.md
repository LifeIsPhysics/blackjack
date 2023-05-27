# blackjack
Terminal Based Black Jack game.

Here are the rules for my version of Blackjack:

    - The dealer gets one card to start (in real life, the dealer gets two, but one is face down so it doesn’t matter at this point).  
    - The player gets two cards to start.  
    - The player goes first.  
    - A player can repeatedly “hit” or “stand”.  
    - If the player “stands”, their turn is over, and their score is calculated based on the cards they have been dealt.  
    - If the player “hits”, they get another card and the value of that card is added to their total score.  
    - An ace normally counts as a 1 or an 11 (whichever is better for the total score). For simplicity, we’ll count it as an 11 here.
    - If the player goes over a score of 21, they bust and lose immediately.
    - The dealer goes after the player.
    - The dealer repeatedly draws until they reach a score of 17 or more, at which point they stand.
    - If the dealer goes over a score of 21, they bust and the player wins immediately.
    - Otherwise, if the player has a higher score than the dealer, the player wins. Otherwise, the player loses (we’ll consider ties as dealer wins for simplicity).  

In our simplified version of Blackjack, we’re not going to keep track of which specific cards the player and the dealer have been dealt. We’ll only track the sum of the values of the cards they have been dealt for the player and dealer. This keeps things simpler.
