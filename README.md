# A War of Whispers – score board

A single-page scorer for *A War of Whispers*, for 2 to 5 players. Open `index.html` in any browser. It has no dependencies and no build step.

## How to use it

1. Pick the number of players (2–5).
2. Enter how many cities each empire controls at game end. Tap an empire name to rename it.
3. For each player, tap their multiplier for every empire: **4** Devout, **3** Dutiful, **2** Affiliated, **0** Unallied, **−1** Opposed.
   Each player holds one token per slot, so picking a slot another empire already has swaps the two. Tap a selected value again to clear it.
4. Use **Adjustments** for anything outside the base scoring, such as expansion bounty tokens, exposed-loyalty penalties or variant rules.

Scores, standings and ties update as you go. A player's score is the sum of (cities × multiplier) over all five empires, plus adjustments. If players tie, the page shows the rulebook tiebreaker: fewest loyalty swaps wins, then most empire cards in hand.

Everything is saved in the browser's local storage on that device. **New game** clears the cities, loyalties and adjustments but keeps the names.
