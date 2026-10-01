# Texas Hold'em

No-limit Texas Hold'em for 2 to 10 players. The table deals, runs the betting, works out the pots and pays the winners. You make the decisions.

## Starting a game

1. Take a seat. Each numbered area on the felt belongs to one seat.
2. Press **+ BOT** to fill empty seats with computer players, or **- BOT** to remove one. You need at least two players, bots included.
3. Press **START GAME**. Everyone starts with $1,000 in chips.

With nobody seated, the table runs a practice game: you play area 1 against bots, with your cards face up in front of you.

## How a hand plays

1. The dealer marker (**D**) moves one seat clockwise each hand.
2. The two players after the dealer post the small blind and the big blind. With only two players, the dealer posts the small blind.
3. Everyone is dealt two private cards. Only you can see yours.
4. There are up to four rounds of betting, with shared cards dealt face up in the middle between them:
   - **Pre-flop**: after the private cards are dealt.
   - **Flop**: three shared cards.
   - **Turn**: a fourth shared card.
   - **River**: a fifth shared card.
5. If more than one player is still in after the river, hands are shown and the best five-card hand wins the pot. You may use any five of your two cards and the five shared cards.

A hand ends early if everyone but one player folds. That player wins the pot without showing.

## Your turn

Your chip total is highlighted when it is your turn, and buttons appear in your area. You have 90 seconds.

- **FOLD**: give up the hand.
- **CHECK** or **CALL**: stay in. Check costs nothing; call matches the current bet. The chips needed to call are placed in your bet pile for you.
- **BET** or **RAISE**: press the **+** button by a chip stack to slide one chip of that value into your bet pile, and **-** by the pile to take one back. When the pile shows the amount you want, press **BET** (or **RAISE**).
- **ALL IN**: bet everything you have.

A raise must be at least as big as the last bet or raise. Until your pile is big enough the button reads **MIN** with the smallest total allowed. You can always go all in for less.

If your time runs out, you check if that is free and fold if it is not.

## Chips

| Chip | Value |
|---|---|
| Blue | $10 |
| Green | $50 |
| Red | $100 |
| Grey | $500 |
| Gold | $1,000 |

The number beside your cards is your total. The table makes change for you when a stack runs short.

## Blinds

Blinds start at 10/20 and go up every 8 hands:

10/20, 20/40, 30/60, 50/100, 100/200, 150/300, 200/400, 300/600, 500/1,000.

## All in and side pots

A player who is all in can only win as much from each opponent as they put in themselves. Bets above that go into a side pot for the players who can still cover them. The table works this out and names the winner of each pot.

A tied pot is split. Any odd chips go to the first winner clockwise from the dealer.

## Hand rankings

From best to worst:

1. **Royal flush**: A, K, Q, J, 10 of one suit.
2. **Straight flush**: five cards in a row, all one suit.
3. **Four of a kind**
4. **Full house**: three of one rank and two of another.
5. **Flush**: five cards of one suit.
6. **Straight**: five cards in a row. An ace can be high (10-J-Q-K-A) or low (A-2-3-4-5).
7. **Three of a kind**
8. **Two pair**
9. **One pair**
10. **High card**

Equal hands are decided by the highest cards not part of the made hand. Suits never break a tie.

## Between hands

- The next dealer presses **DEAL** to start the next hand. If nobody does, it deals after 30 seconds.
- A player out of chips can press **REBUY** for another $1,000. A bot out of chips leaves the table.
- **END GAME** stops play and returns to the start screen. A game in progress can be picked up again with **RESUME**.
- The game ends when one player holds all the chips.
