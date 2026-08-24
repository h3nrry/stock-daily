# Stock Market Daily Analysis

This folder holds daily analysis of world stock markets, major currencies, bonds, ETFs, and commodities (oil, gold, bitcoin). Each trading day gets its own dated subfolder; open that day's `README.md` first — it's the index for everything inside.

## Folder naming

Each daily subfolder is named `YYMMDD` (two-digit year, month, day), e.g. `260824` = August 24, 2026. New days are added as new sibling folders — nothing here is overwritten day to day.

## What's inside each daily folder

| File | Covers |
|---|---|
| `README.md` | The day's index: an index-comparison table across every market, a "where the money is flowing" synthesis, and a short summary + pointer for every file below. Start here. |
| `usa.md` | US equities (Dow/S&P/Nasdaq), US Treasury yields, US investment-grade & high-yield corporate bond spreads, and US equity ETF flows (SPY/VOO/QQQ/QQQM etc.) |
| `taiwan.md` | Taiwan's TAIEX, sector and stock-level detail, foreign investor (外資) money flow, Taiwan-listed ETFs (0050, 00878, 00919), and bullish stock candidates |
| `japan.md` | Japan's Nikkei 225, drivers, JPX foreign-investor weekly flow data, yen/BOJ context, stocks and sectors to watch |
| `korea.md` | Korea's KOSPI/KOSDAQ, foreign/institutional/individual investor flow, stocks to watch |
| `hongkong.md` | Hong Kong's Hang Seng and Hang Seng TECH, mainland-tech read-through, stocks to watch |
| `southeast_asia.md` | Singapore (STI), Indonesia (IHSG/JCI), Malaysia (FBM KLCI), and Thailand (SET) — one file, one section per country |
| `uk_europe.md` | UK (FTSE 100), Germany (DAX), France (CAC 40), and the broader STOXX 600 — one file, one section per market |

Oil, gold, and bitcoin are covered directly in each day's `README.md` rather than in their own files.

## Conventions used throughout

- **Bilingual naming:** every stock, company, and fund name is shown with both its English name/ticker and the local-language name (Chinese for Taiwan/Hong Kong-linked names, Korean for Korea, Japanese for Japan) — e.g. TSMC / 台積電, Samsung Electronics / 삼성전자. Key financial terms get the local term in parentheses too (money flow / 資金流向, foreign investors / 外資 / 外国人 / 海外投資家, net sell / 賣超 / 売り越し).
- **Money-flow framing:** each market file distinguishes a single day's net buy/sell from the underlying multi-day or multi-month trend, and calls out whether foreign selling is concentrated in one stock/sector (often not a real risk signal) or broad-based.
- **Stock ideas come with risk notes:** every "stocks to watch" table pairs the bullish rationale with what to watch for / what could go wrong — none of it is a buy recommendation.
- **Every file ends with a disclaimer:** this is informational analysis, not financial advice; figures are current as of the time of writing and can change intraday.

## How this gets built

Each day's files are researched fresh from current news and market data (index levels, sector moves, money flow, currencies, bonds, ETFs) and written in this structure. The structure itself has grown incrementally — it started as a single Taiwan file and expanded over time to the full set above. If you want a market or asset class added, removed, or restructured (e.g. splitting Southeast Asia into individual files, adding China A-shares or India), just ask — the format will adapt and the convention carries forward to future days automatically.

---
© 2026 Henrry Andrian‍​‌​​‌​​​​‌‌​​‌​‌​‌‌​‌‌‌​​‌‌‌​​‌​​‌‌‌​​‌​​‌‌‌‌​​‌​‌​​​​​‌​‌‌​‌‌‌​​‌‌​​‌​​​‌‌‌​​‌​​‌‌​‌​​‌​‌‌​​​​‌​‌‌​‌‌‌​​​‌‌​​‌​​​‌‌​​​​​​‌‌​​‌​​​‌‌​‌‌​‍. All rights reserved.
