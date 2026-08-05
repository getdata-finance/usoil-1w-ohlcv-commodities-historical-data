# USOIL 1w OHLCV Commodities Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-2_092_rows-blue)](https://getdata.finance/datasets/usoil) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/usoil)

### -> [**Download the full USOIL dataset on getdata.finance**](https://getdata.finance/datasets/usoil)

**USOIL 1w OHLCV commodities historical data** — ultra high-quality 1w OHLCV for **WTI Crude Oil**. Global commodity sessions — Asia, Europe and US coverage for futures-style market activity. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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
- **Global commodity sessions — Asia, Europe and US coverage for futures-style market activity**
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1w`) · **9 timeframes** on [getdata.finance](https://getdata.finance/datasets/usoil) · **2,092** `1m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `1w` sample updated in sync

> **Sample on GitHub** · `USOIL_1w.csv` (36 rows, `2025-11-27` -> `2026-07-30`). **Full archive on [getdata.finance](https://getdata.finance/datasets/usoil)** — **2,092** `1m` rows (~0.16 MB), **9 timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 12H · 3D · 1W), `1986-07-03` -> `2026-07-30`.

## Download sample

**[USOIL_1w.csv](https://github.com/getdata-finance/usoil-1w-ohlcv-commodities-historical-data/blob/main/USOIL_1w.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/usoil-1w-ohlcv-commodities-historical-data/main/USOIL_1w.csv)) · [GitHub Releases](https://github.com/getdata-finance/usoil-1w-ohlcv-commodities-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/usoil-1w-ohlcv-commodities-historical-data/](https://getdata-finance.github.io/usoil-1w-ohlcv-commodities-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/usoil](https://getdata.finance/datasets/usoil)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/usoil))** |
|---|--:|---|
| Instrument | WTI Crude Oil · Commodities | WTI Crude Oil · Commodities |
| Timeframes | `1w` (sample) | **9** — 1m · 3m · 5m · 15m · 30m · 1H · 12H · 3D · 1W |
| 1m rows | 36 | **2,092** |
| Size | 0.00 MB | ~0.16 MB |
| Period | `2025-11-27` -> `2026-07-30` | `1986-07-03` -> `2026-07-30` |
| File | `USOIL_1w.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/usoil) |
| Coverage report | — | [USOIL coverage](https://getdata.finance/coverage/usoil) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`1w` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/usoil)**, each full asset archive is delivered as a ZIP with **9 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **12H** · **3D** · **1W**

GitHub = `1w` sample · [getdata.finance](https://getdata.finance/datasets/usoil) = all **9** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `1w` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`USOIL_1w.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2025-11-27T00:00:00+00:00 | 58.54 | 59.95 | 58.251 | 59.085 | 146588 |
| 2025-12-04T00:00:00+00:00 | 59.085 | 60.476 | 57.634 | 58.934 | 150618 |
| 2025-12-11T00:00:00+00:00 | 58.934 | 58.934 | 54.964 | 56.885 | 204564 |
| 2025-12-18T00:00:00+00:00 | 56.885 | 58.735 | 55.594 | 58.376 | 176363 |
| 2025-12-25T00:00:00+00:00 | 58.376 | 58.856 | 56.635 | 57.581 | 109279 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-07-02T00:00:00+00:00 | 68.074 | 76.056 | 67.026 | 74.759 | 606554 |
| 2026-07-09T00:00:00+00:00 | 74.759 | 81.256 | 70.755 | 80.229 | 1005031 |
| 2026-07-16T00:00:00+00:00 | 80.229 | 88.591 | 78.56 | 86.466 | 934386 |
| 2026-07-23T00:00:00+00:00 | 86.466 | 93.486 | 77.764 | 84.636 | 1090116 |
| 2026-07-30T00:00:00+00:00 | 84.636 | 85.924 | 81.19 | 82.516 | 235131 |

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
print(df.resample('1h').agg({'open': 'first', 'high': 'max',
                              'low': 'min', 'close': 'last', 'volume': 'sum'}).head())
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
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1min')
print(pf.stats())
```

## Download full data

The complete **USOIL** archive on **[getdata.finance](https://getdata.finance/datasets/usoil)** includes **9 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 12H · 3D · 1W) — **2,092** rows at `1m`, plus all other timeframes in the same ZIP.

**[-> Get the full USOIL dataset on getdata.finance](https://getdata.finance/datasets/usoil)**

---
*GetData · USOIL 1w OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/usoil) · 2026-08-05 UTC*
