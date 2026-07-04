# EUSTX50 12h OHLCV Index Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-391_rows-blue)](https://ork.ad/) [![Updated](https://img.shields.io/badge/weekly_update-every_Sunday-green)](https://ork.ad/) [![Full data on ork.ad](https://img.shields.io/badge/download-ork.ad-orange)](https://ork.ad/)

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
- **Free evaluation sample** on GitHub (`12h`) · **13 timeframes** on [ork.ad](https://ork.ad/) · **391** `12h` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [ork.ad](https://ork.ad/) every **Sunday**; GitHub `12h` sample updated in sync

> **Sample on GitHub** · `EUSTX50_12h.csv` (377 rows, `2025-10-02` → `2026-07-02`). **Full archive on [ork.ad](https://ork.ad/)** — **391** `12h` rows (~0.02 MB), **13 timeframes** (``1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W``), `2025-09-23` → `2026-07-02`.

## Download sample

**[EUSTX50_12h.csv](https://github.com/ork-ad/eustx50-12h-ohlcv-index-historical-data/blob/main/EUSTX50_12h.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/ork-ad/eustx50-12h-ohlcv-index-historical-data/main/EUSTX50_12h.csv)) · [GitHub Releases](https://github.com/ork-ad/eustx50-12h-ohlcv-index-historical-data/releases) when the release workflow is active.

## GitHub Pages

Interactive chart & stats: **[https://ork-ad.github.io/eustx50-12h-ohlcv-index-historical-data/](https://ork-ad.github.io/eustx50-12h-ohlcv-index-historical-data/)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([ork.ad](https://ork.ad/))** |
|---|--:|---|
| Instrument | Euro Stoxx 50 · Stock index | Euro Stoxx 50 · Stock index |
| Timeframes | `12h` (sample) | **13** — `1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W` |
| 12h rows | 377 | **391** |
| Size | 0.02 MB | ~0.02 MB |
| Period | `2025-10-02` → `2026-07-02` | `2025-09-23` → `2026-07-02` |
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
| 2025-10-02T12:00:00Z | 5672.287 | 5681.287 | 5646.766 | 5662.36 | 4678.0 |
| 2025-10-03T00:00:00Z | 5662.36 | 5674.797 | 5647.776 | 5649.276 | 3675.0 |
| 2025-10-03T12:00:00Z | 5649.276 | 5665.287 | 5647.296 | 5660.337 | 4020.0 |
| 2025-10-06T00:00:00Z | 5660.337 | 5663.687 | 5611.666 | 5653.687 | 7071.0 |
| 2025-10-06T12:00:00Z | 5653.687 | 5655.667 | 5630.686 | 5640.726 | 2795.0 |

**Last rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| time | open | high | low | close | volume |
| 2026-06-30T12:00:00Z | 6319.86 | 6348.84 | 6294.84 | 6343.4 | 6204.0 |
| 2026-07-01T00:00:00Z | 6343.4 | 6343.4 | 6299.79 | 6300.8 | 5911.0 |
| 2026-07-01T12:00:00Z | 6300.8 | 6308.8 | 6274.29 | 6291.36 | 9159.0 |
| 2026-07-02T00:00:00Z | 6291.36 | 6337.44 | 6268.92 | 6336.44 | 7266.0 |

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

The complete **EUSTX50** archive on **[ork.ad](https://ork.ad/)** includes **13 OHLCV timeframes** (`1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W`) — **391** rows at `12h`, plus all other timeframes in the same ZIP.

**[→ Get the full EUSTX50 dataset on ork.ad](https://ork.ad/)**

---
*GetData · EUSTX50 12h OHLCV sample on GitHub · Full historical data on [ork.ad](https://ork.ad/) · 2026-07-04 UTC*