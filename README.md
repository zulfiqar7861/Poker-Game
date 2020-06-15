# Playing Cards in Java 

As a feature of a bigger venture of making applications that manage playing a game of cards (Cribbage scores, Poker probabilities, and so on.), I've chosen to make an open source library for managing playing a game of cards and assortments of playing a game of cards. 

The sorts I've characterized are: 

### Deck (class) 

- has many 'Card's 

- can repeat over the 'Card's by 'Rank' 

- can emphasize over the 'Card's by 'Suit' 

- can render itself to a 'String' 

### Card (class) 

- has a 'Position' 

- has a 'Suit' 

- can render itself to a 'String' 

### Rank (enum) 

- has an 'int' record 

- can render itself to a 'String' 

### Suit (enum) 

- can render itself to a 'String' 

- can 'beautiful' render itself to a 'String' with extravagant UTF-8 characters, for example, ♣ 

### CribbageCalculator 

- takes in a deck and figures a score 

- restores the score 

- restores the assortment of score portrayals 

Task: 

1. Recreate a game between 4 players. 

2. Haphazardly bargain them cards from a deck. 

3. Decide the champ.
