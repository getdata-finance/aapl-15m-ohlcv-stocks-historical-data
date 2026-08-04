# AAPL 15m OHLCV US stocks Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-80_670_rows-blue)](https://getdata.finance/datasets/aapl) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/aapl)

### -> [**Download the full AAPL dataset on getdata.finance**](https://getdata.finance/datasets/aapl)

**AAPL 15m OHLCV us stocks historical data** — ultra high-quality 15m OHLCV for **AAPL**. US equity cash and extended sessions — institutional-style OHLCV candles for US stocks. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [GitHub Pages preview](#github-pages)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on GetData](#timeframes-on-getdata)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Code examples](#code-examples)
- [Download full data on getdata.finance](#download-full-data-on-getdata)

## Why this dataset?

- **Ultra high-quality 15m OHLCV** for **AAPL** (US stocks)
- **US equity cash and extended sessions — institutional-style OHLCV candles for US stocks**
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`15m`) · **9 timeframes** on [getdata.finance](https://getdata.finance/datasets/aapl) · **80,670** `1m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `15m` sample updated in sync

> **Sample on GitHub** · `AAPL_15m.csv` (3,250 rows, `2026-02-02` -> `2026-07-31`). **Full archive on [getdata.finance](https://getdata.finance/datasets/aapl)** — **80,670** `1m` rows (~6.13 MB), **9 timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 12H · 3D · 1W), `2011-05-09` -> `2026-07-31`.

## Download sample

**[AAPL_15m.csv](https://github.com/getdata-finance/aapl-15m-ohlcv-stocks-historical-data/blob/main/AAPL_15m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/aapl-15m-ohlcv-stocks-historical-data/main/AAPL_15m.csv)) · [GitHub Releases](https://github.com/getdata-finance/aapl-15m-ohlcv-stocks-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/aapl-15m-ohlcv-stocks-historical-data/](https://getdata-finance.github.io/aapl-15m-ohlcv-stocks-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/aapl](https://getdata.finance/datasets/aapl)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/aapl))** |
|---|--:|---|
| Instrument | AAPL · US stocks | AAPL · US stocks |
| Timeframes | `15m` (sample) | **9** — 1m · 3m · 5m · 15m · 30m · 1H · 12H · 3D · 1W |
| 1m rows | 3,250 | **80,670** |
| Size | 0.31 MB | ~6.13 MB |
| Period | `2026-02-02` -> `2026-07-31` | `2011-05-09` -> `2026-07-31` |
| File | `AAPL_15m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/aapl) |
| Coverage report | — | [AAPL coverage](https://getdata.finance/coverage/aapl) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`15m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/aapl)**, each full asset archive is delivered as a ZIP with **9 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **12H** · **3D** · **1W**

GitHub = `15m` sample · [getdata.finance](https://getdata.finance/datasets/aapl) = all **9** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `15m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`AAPL_15m.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-02-02T14:30:00+00:00 | 257.05 | 262.04 | 257.05 | 259.15 | 4736 |
| 2026-02-02T14:45:00+00:00 | 259.15 | 262.03 | 258.99 | 261.37 | 3693 |
| 2026-02-02T15:00:00+00:00 | 261.37 | 262.8 | 261.27 | 262.75 | 3628 |
| 2026-02-02T15:15:00+00:00 | 262.75 | 263.35 | 262.14 | 263.14 | 3579 |
| 2026-02-02T15:30:00+00:00 | 263.14 | 263.46 | 261.69 | 261.98 | 3109 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-07-31T18:45:00+00:00 | 302.11 | 302.76 | 301.84 | 302.62 | 1368 |
| 2026-07-31T19:00:00+00:00 | 302.62 | 304.64 | 302.56 | 304.32 | 2277 |
| 2026-07-31T19:15:00+00:00 | 304.32 | 305.49 | 304.32 | 305.45 | 2537 |
| 2026-07-31T19:30:00+00:00 | 305.45 | 306.43 | 304.82 | 306.33 | 3075 |
| 2026-07-31T19:45:00+00:00 | 306.33 | 310.41 | 305.9 | 308.87 | 5924 |

## Schema

| Column | Description |
| --- | --- |
| `datetime` | Bar open timestamp (UTC, ISO-8601). |
| `open` | Opening price of the candlestick bar. |
| `high` | Highest price during the bar. |
| `low` | Lowest price during the bar. |
| `close` | Closing price of the candlestick bar. |
| `volume` | Tick volume (number of price updates) during the bar. |

```text
datetime,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('AAPL_15m.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
print(df.resample('1h').agg({'open': 'first', 'high': 'max',
                              'low': 'min', 'close': 'last', 'volume': 'sum'}).head())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('AAPL_15m.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)

class PandasData(bt.feeds.PandasData):
    params = (('datetime', None), ('open', 'open'), ('high', 'high'),
              ('low', 'low'), ('close', 'close'), ('volume', 'volume'))

cerebro = bt.Cerebro()
cerebro.adddata(PandasData(dataname=df))
# cerebro.addstrategy(YourStrategy)
# cerebro.run()
```

### vectorbt

```python
import pandas as pd
import vectorbt as vbt

df = pd.read_csv('AAPL_15m.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1min')
print(pf.stats())
```

## Download full data

The complete **AAPL** archive on **[getdata.finance](https://getdata.finance/datasets/aapl)** includes **9 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 12H · 3D · 1W) — **80,670** rows at `1m`, plus all other timeframes in the same ZIP.

**[-> Get the full AAPL dataset on getdata.finance](https://getdata.finance/datasets/aapl)**

---
*GetData · AAPL 15m OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/aapl) · 2026-08-04 UTC*
