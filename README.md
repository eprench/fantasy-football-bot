# fantasy-football-bot
Automate playing Yahoo Fantasy Football

# Usage
There are two components:
- `scraper.py`
  - web-scrapes the current and available players, and their point forecasts for the rest of the season
  - requires setting environment variables YAHOO_FOOTBALL_USER and YAHOO_FOOTBALL_PASS with your Yahoo Fantasy Football credentials
- `optimize.py`
  - optimize the assignment of players to positions each week to maximize remaining season discounted total points (points this week are worth more than points in future weeks)
  - decides which players to add and drop
  - optimization is repeated for current roster, for one player add/drop, two player add/drops, etc.

# Contribution
Please add Issues or submit Pull requests!
