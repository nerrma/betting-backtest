# Betting Backtest

The main work is in the notebook `kelly_backtest.ipynb`. Here, I do some basic data exploration and try to estimate the probability distribution of the winning odds to then backtest the strategy. This strategy places Kelly bets in a risk-averse fashion, avoiding bets with higher odds.

The data sets are as follows:

- 'epl' - Odds from games of the English Premier League (from the given year)
- 'it' - Odds from games of Serie A (Italian top flight league, from the given year)
- 'de' - Odds from games of the Bundesliga (German top flight league, from the given year)
