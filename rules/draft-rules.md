# Draft Rules

## Setup

- Each player starts with 20 health.
- Each player shuffles a deck of 30 cards and draws 5.
- Both players share the same card list (see `cards/`).

## A Round

- Both players gain energy equal to the round number, up to a maximum of 10.
- Players alternate: play a card, or attack with one unit.
- A unit cannot attack on the round it is played.
- Unspent energy does not carry over.

## Combat

- An attacking unit deals its attack to the defending unit's health.
- The defender deals its attack back.
- A unit at 0 health or less is removed.

## Winning

- A player at 0 health loses.

## My rule

Player's card's attack may carry over through a defending card if they caused over +1 damage to its remaining defense.
Example: (Player 1) plays 10. (Player 2) plays 8. (Player 1) 10 beats 8 by +2. (Player 1) causes 1 damage to player 2.
I think this will cause very unbalanced fights to be more costly and slowly chip at every players large health pool quicker. 
