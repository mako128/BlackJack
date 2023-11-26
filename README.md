![Black Jack Banner](https://github.com/mako128/BlackJack/blob/main/markdown%20images/Black_Jack.png)

# How to play

The player starts with two cards and the dealer also starts with two but only one is visible
The player can take a hit as many times as they like as long as they don't go over 21.
Once the player goes over 21 they are bust and can't take any more cards so they are forced to stand.
The aim of the game is to get a higher value than the dealer without going over 21

The dealer has to keep drawing cards until they reach 17 or over and then they have the choice to stand.  Ace values count as 1 as long as you're under 21 and at least have 1 ace.

# Logic

## buildDeck Method

I built the deck by making an array of all the suits and all the card values needed for a game of BlackJack.
I then used a for loop using the length of the array types, and within that for loop I used another for loop for the length of the array values to create a new object called <span style="color: green;">card</span> that has both the concatenated value and type of card using the index of both arrays.
![buildDeckSnippet](https://github.com/mako128/BlackJack/blob/main/markdown%20images/buildDeckSnippet.png)

## shuffleDeck Method

I shuffled the deck of cards by using a for loop and in that for loop i created a random card and swapped the random card with the current card in the array.
![buildDeckSnippet](https://github.com/mako128/BlackJack/blob/main/markdown%20images/shuffleDeckSnippet.png)
