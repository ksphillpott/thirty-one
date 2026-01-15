# THIRTY-ONE

A roguelike card game inspired by the classic card game 31, with modifiers, spirits, marks, and more.

## Play Online

Visit the GitHub Pages deployment to play directly in your browser.

## Features

- **9 Unique Decks** - Standard, Vampire, Gambler, Alchemist, Phoenix, Merchant, Wild, Glass, Blessed
- **8 Ascension Levels** - Increasing difficulty with stacking penalties
- **32 Modifiers** - Value, Suit, Threshold, Action, Hand, Entropy, and Synergy categories
- **12 Relics** - Powerful passive abilities unlocked through achievements
- **8 Spirits** - Companions that grant bonuses but abandon you if mistreated
- **5 Card Marks** - Flame, Ice, Crown, Echo, Debt
- **18 Bosses** - Unique rule-breaking challenges at the end of each act
- **7 Challenges** - Special game modes with unique constraints
- **Daily Runs** - Seeded daily challenges
- **Endless Mode** - Keep playing after Act 3

## Local Development

Simply open `index.html` in a browser, or use any local server:

```bash
# Python
python -m http.server 8000

# Node.js
npx serve
```

## How to Play

1. Draw cards to build a hand
2. Score is the sum of cards in your best suit
3. Reach the target (17+) without busting (over 31)
4. Collect modifiers and upgrades between rounds
5. Beat the boss on round 6 to advance to the next act
