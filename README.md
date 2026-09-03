# USOIL 1w OHLCV Commodities Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-2_096_rows-blue)](https://getdata.finance/datasets/usoil) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/usoil)

### -> [**Download the full USOIL dataset on getdata.finance**](https://getdata.finance/datasets/usoil)

**USOIL 1w OHLCV commodities historical data** — ultra high-quality 1w OHLCV for **WTI Crude Oil**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 1w OHLCV** for **WTI Crude Oil** (Commodities)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1w`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/usoil) · **2,096** `1w` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `1w` sample updated in sync

> **Sample on GitHub** · `USOIL_1w.csv` (8 rows, `2026-07-09` -> `2026-08-27`, 0.57 KB). **Full archive on [getdata.finance](https://getdata.finance/datasets/usoil)** — **2,096** `1w` rows (full `1m`: 6,029,418), **11 timeframes**, `1986-07-03` -> `2026-08-27`.

## Download sample

**[USOIL_1w.csv](https://github.com/getdata-finance/usoil-1w-ohlcv-commodities-historical-data/blob/main/USOIL_1w.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/usoil-1w-ohlcv-commodities-historical-data/main/USOIL_1w.csv)) · [GitHub Releases](https://github.com/getdata-finance/usoil-1w-ohlcv-commodities-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/usoil-1w-ohlcv-commodities-historical-data/](https://getdata-finance.github.io/usoil-1w-ohlcv-commodities-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/usoil](https://getdata.finance/datasets/usoil)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/usoil))** |
|---|--:|---|
| Instrument | WTI Crude Oil · Commodities | WTI Crude Oil · Commodities |
| Timeframes | `1w` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 1w rows | 8 | **2,096** |
| Size | 0.57 KB | full ZIP on [getdata.finance](https://getdata.finance/datasets/usoil) |
| Period | `2026-07-09` -> `2026-08-27` | `1986-07-03` -> `2026-08-27` |
| File | `USOIL_1w.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/usoil) |
| Coverage report | — | [USOIL coverage](https://getdata.finance/coverage/usoil) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`1w` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/usoil)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `1w` sample · [getdata.finance](https://getdata.finance/datasets/usoil) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `1w` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`USOIL_1w.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-07-09T00:00:00+00:00 | 71.803 | 81.259 | 70.464 | 79.553 | 1140462 |
| 2026-07-16T00:00:00+00:00 | 79.553 | 93.489 | 78.594 | 92.358 | 1207759 |
| 2026-07-23T00:00:00+00:00 | 92.358 | 92.803 | 77.767 | 83.939 | 1496601 |
| 2026-07-30T00:00:00+00:00 | 83.939 | 86.353 | 74.207 | 78.237 | 914325 |
| 2026-08-06T00:00:00+00:00 | 78.237 | 84.598 | 76.542 | 81.174 | 730727 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-07-30T00:00:00+00:00 | 83.939 | 86.353 | 74.207 | 78.237 | 914325 |
| 2026-08-06T00:00:00+00:00 | 78.237 | 84.598 | 76.542 | 81.174 | 730727 |
| 2026-08-13T00:00:00+00:00 | 81.174 | 87.672 | 80.682 | 86.199 | 670280 |
| 2026-08-20T00:00:00+00:00 | 86.199 | 87.497 | 80.739 | 84.134 | 458461 |
| 2026-08-27T00:00:00+00:00 | 84.134 | 92.274 | 82.834 | 91.287 | 458128 |

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

df = pd.read_csv('USOIL_1w.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('USOIL_1w.csv', parse_dates=['datetime'])
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

df = pd.read_csv('USOIL_1w.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1W')
print(pf.stats())
```

## Download full data

The complete **USOIL** archive on **[getdata.finance](https://getdata.finance/datasets/usoil)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **2,096** rows at `1w`, plus all other timeframes in the same ZIP.

**[-> Get the full USOIL dataset on getdata.finance](https://getdata.finance/datasets/usoil)**

---
*GetData · USOIL 1w OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/usoil)*
