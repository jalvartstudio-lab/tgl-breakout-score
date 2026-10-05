# How a 0–6 breakout score works (Gold & S&P 500) — with an open, timestamped log

TGL Macro Alerts watches **Gold (xyz:GOLD)** and the **S&P 500 (xyz:SP500)** on Hyperliquid's xyz dex across 15-minute, 1-hour and 4-hour windows. When a window looks unusual, it publishes a breakout **alert** with a **0–6 score** and the reason behind it — nothing more.

## The 0–6 score
Each alert is scored 0–6 from objective, window-relative conditions (e.g. *breakout above the prior 20-candle high*, *range ×N ATR14*). The score is not a forecast or a recommendation — it's a compact measure of how unusual the move is right now.

## The open log
Every alert is published to a **public log**, with a delay, including its score and reasons:
https://theglitchlist.com/breakout-log/ — quiet days included.

## How to read one alert
1. Market + window (Gold / S&P 500 · 15m / 1h / 4h)
2. The 0–6 score
3. The reasons (the "why")
4. The invalidation level (where the idea is wrong)

## Links
- Live alerts → https://theglitchlist.com/macro-alerts/
- Score guide → https://theglitchlist.com/score-guide/
- Open datasets → https://www.kaggle.com/jalvartstudio

*Not financial advice. Alerts are informational only.*
