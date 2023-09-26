# Blackjack Game Pseudocode

## Card Class
* Should have string conversion (__str__)
* Constructor to take as parameter the Suit and Rank
    * Suit, Rank, Value will be class variables for Card


## Deck Class

### Constructor 
* Initialize 52 card deck      
* Method to deal cards 
    * Takes as input the player instance or computer instance


## Player Class
### Constructor
* Instance Attributes
    * Balance (keep track of balance)
        * We can specify amount we want to start with or it will default to 0

### Methods

* ```python
    deal_hand(self):
        
```
* ```python 
    bet(self,amount):
        self.amount = amount
```

