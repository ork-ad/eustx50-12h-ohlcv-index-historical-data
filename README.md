# EUSTX50 12h OHLCV Index Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-7_044_rows-blue)](https://ork.ad/) [![Updated](https://img.shields.io/badge/weekly_update-every_Sunday-green)](https://ork.ad/) [![Full data on ork.ad](https://img.shields.io/badge/download-ork.ad-orange)](https://ork.ad/)

### → [**Download the full EUSTX50 dataset on ork.ad**](https://ork.ad/)

**EUSTX50 12h OHLCV Stock index historical data** — ultra high-quality 12h OHLCV for **Euro Stoxx 50**. Global cash and extended index sessions — Asia, Europe and US coverage, not US-hours only. Clean `time, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [GitHub Pages preview](#github-pages)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on ork.ad](#timeframes-on-orkad)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Code examples](#code-examples)
- [Download full data on ork.ad](#download-full-data)

## Why this dataset?

- **Ultra high-quality 12h OHLCV** for **Euro Stoxx 50** (Stock index)
- **Global cash and extended index sessions — Asia, Europe and US coverage, not US-hours only**
- **Clean CSV schema** — `time, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`12h`) · **13 timeframes** on [ork.ad](https://ork.ad/) · **7,044** `12h` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [ork.ad](https://ork.ad/) every **Sunday**; GitHub `12h` sample updated in sync

> **Sample on GitHub** · `EUSTX50_12h.csv` (375 rows, `2025-10-03` → `2026-07-03`). **Full archive on [ork.ad](https://ork.ad/)** — **7,044** `12h` rows (~0.39 MB), **13 timeframes** (``1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W``), `2012-08-27` → `2026-07-03`.

## Download sample

**[EUSTX50_12h.csv](https://github.com/ork-ad/eustx50-12h-ohlcv-index-historical-data/blob/main/EUSTX50_12h.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/ork-ad/eustx50-12h-ohlcv-index-historical-data/main/EUSTX50_12h.csv)) · [GitHub Releases](https://github.com/ork-ad/eustx50-12h-ohlcv-index-historical-data/releases) when the release workflow is active.

## GitHub Pages

Interactive chart & stats: **[https://ork-ad.github.io/eustx50-12h-ohlcv-index-historical-data/](https://ork-ad.github.io/eustx50-12h-ohlcv-index-historical-data/)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([ork.ad](https://ork.ad/))** |
|---|--:|---|
| Instrument | Euro Stoxx 50 · Stock index | Euro Stoxx 50 · Stock index |
| Timeframes | `12h` (sample) | **13** — `1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W` |
| 12h rows | 375 | **7,044** |
| Size | 0.02 MB | ~0.39 MB |
| Period | `2025-10-03` → `2026-07-03` | `2012-08-27` → `2026-07-03` |
| File | `EUSTX50_12h.csv` | ZIP on [ork.ad](https://ork.ad/) |
| Updates | Weekly (Sunday) — GitHub sample | Weekly (Sunday) — all timeframes |

## Timeframes on ork.ad

This GitHub repository ships a **`12h` evaluation sample** only. On **[ork.ad](https://ork.ad/)**, each full asset archive is delivered as a ZIP with **13 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **2H** · **4H** · **8H** · **12H** · **16H** · **1D** · **1W**

GitHub = `12h` sample · [ork.ad](https://ork.ad/) = all **13** timeframes above for the same instrument.

## Weekly updates

- **[ork.ad](https://ork.ad/)** — Full datasets on ork.ad are updated every Sunday.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Sunday), in sync with ork.ad.

When a new `12h` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`EUSTX50_12h.csv`**:

**First rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2025-10-03T12:00:00Z | 5656.25 | 5665.74 | 5648.22 | 5660.79 | 3211.0 |
| 2025-10-06T00:00:00Z | 5660.79 | 5664.14 | 5612.11 | 5643.11 | 8044.0 |
| 2025-10-06T12:00:00Z | 5643.11 | 5649.13 | 5631.13 | 5641.17 | 1822.0 |
| 2025-10-07T00:00:00Z | 5641.17 | 5650.54 | 5618.52 | 5641.52 | 3741.0 |
| 2025-10-07T12:00:00Z | 5641.52 | 5641.52 | 5608.52 | 5611.59 | 3292.0 |

**Last rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| time | open | high | low | close | volume |
| 2026-07-01T12:00:00Z | 6300.42 | 6305.44 | 6277.42 | 6291.99 | 4735.0 |
| 2026-07-02T00:00:00Z | 6291.99 | 6403.58 | 6270.05 | 6394.07 | 11607.0 |
| 2026-07-02T12:00:00Z | 6394.07 | 6396.07 | 6335.07 | 6368.12 | 11661.0 |
| 2026-07-03T00:00:00Z | 6368.12 | 6420.17 | 6368.12 | 6419.16 | 6516.0 |

## Schema

```text
time,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('EUSTX50_12h.csv', parse_dates=['time'])
df.set_index('time', inplace=True)
print(df.describe())
print(df.resample('1h').agg({'open': 'first', 'high': 'max',
                              'low': 'min', 'close': 'last', 'volume': 'sum'}).head())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('EUSTX50_12h.csv', parse_dates=['time'])
df.set_index('time', inplace=True)

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

df = pd.read_csv('EUSTX50_12h.csv', parse_dates=['time'])
close = df.set_index('time')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='12h')
print(pf.stats())
```

## Download full data

The complete **EUSTX50** archive on **[ork.ad](https://ork.ad/)** includes **13 OHLCV timeframes** (`1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W`) — **7,044** rows at `12h`, plus all other timeframes in the same ZIP.

**[→ Get the full EUSTX50 dataset on ork.ad](https://ork.ad/)**

---
*GetData · EUSTX50 12h OHLCV sample on GitHub · Full historical data on [ork.ad](https://ork.ad/) · 2026-07-06 UTC*