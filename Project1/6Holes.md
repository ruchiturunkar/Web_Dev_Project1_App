# 6 Holes
## Authors
* Anagha Bhosale
* Ruchit Urunkar


### Game description

6 holes is a draw-and-discard game played with usual 52 deck of cards (+1 wild card joker). It is played by two players, each having 6 cards at any given time. The aim is to find a match for each card as early as one can, such that there are three matching pairs of cards.

The game involves keeping the six cards blind initially, such that there are three cards in one row. Thus, resulting in 2 rows of 3 cards each. Players take turns and decide to reveal the card or draw a card from the deck.Each card is associated with a value. The cards numbered from 2 to 10 are assigned the same respective values, whereas the King, Queen, Jack, Ace, Joker are assigned 0, 12, 11, 1, -5 respectively.

Rules of the game involve making pairs in the columns. Each matching pair in the column results in a score of 0. Thus, the goal of the game is to achieve minimum score possible. The pairs can be formed between the same cards (e.g. Queen-Queen, 7-7). The card type whether hearts, spade, diamond, club does not matter. The Joker card is a wild card and matches with any card and the player also achieves a bonus score of -5.

The game initiates by revealing the two cards of the middle column for both the players. On each turn a player can draw a card from the deck or pick up the discarded card of the opponent and place it on the unveiled side cards or unveil the side cards. But the side cards once unveiled cannot be swapped with the card picked from the deck or opponents discarded card. The side cards can be swapped only if they remain blind.

Each player aims to make a match in the columns. A pair in the columns gives a score of 0, thus strategy of the game is to get the minimum possible score by matching the cards in the subsequent pick or trying to match with the unveiled side card. A player should try to save the minimum valued cards or discard the cards that are of no use to the opponent. The game ends when either of the player attains all the matches. Upon such instance the opponent gets his turn to pick card and swap with the side card if not unveiled or discard the card if he feels that the card picked up from the deck is having higher value than the unveiled card.

Once he completes his turn, the score is calculated based on the pairs in the columns. If a column has a pair, the value associated with the column is 0. If the column does not have a match, then score is the sum of the value assigned to the cards (e.g. column 1 has Ace and 7, column 2 has two Queens, column 3 has 2 and Joker, then in such case the score is (column 1=>6, column 2=>0, column 3=>-3). Effective score will be 3. Thus, 6 such rounds are played, and the player achieving minimum score as total is declared as the winner.
