# GER30 1m OHLCV Index Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-2_331_838_rows-blue)](https://getdata.finance/datasets/ger30) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/ger30)

### -> [**Download the full GER30 dataset on getdata.finance**](https://getdata.finance/datasets/ger30)

**GER30 1m OHLCV index historical data** — ultra high-quality 1m OHLCV for **DAX 40 (GER30)**. Clean `time, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on GetData](#timeframes-on-getdata)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Download full data on getdata.finance](#download-full-data-on-getdata)

## Why this dataset?

- **Ultra high-quality 1m OHLCV** for **DAX 40 (GER30)** (Index)
- **Clean CSV schema** — `time, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1m`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/ger30) · **2,331,838** `1m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `1m` sample updated in sync

> **Sample on GitHub** · `GER30_1m.csv` (55,440 rows, `2026-06-26` -> `2026-09-02`). **Full archive on [getdata.finance](https://getdata.finance/datasets/ger30)** — **2,331,838** `1m` rows, **11 timeframes**, `2019-01-02` -> `2026-09-02`.

## Download sample

**[GER30_1m.csv](https://github.com/getdata-finance/ger30-1m-ohlcv-index-historical-data/blob/main/GER30_1m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/ger30-1m-ohlcv-index-historical-data/main/GER30_1m.csv))

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/ger30))** |
|---|--:|---|
| Instrument | DAX 40 (GER30) · Index | DAX 40 (GER30) · Index |
| Timeframes | `1m` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 1m rows | 55,440 | **2,331,838** |
| Period | `2026-06-26` -> `2026-09-02` | `2019-01-02` -> `2026-09-02` |
| File | `GER30_1m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/ger30) |
| Coverage report | — | [GER30 coverage](https://getdata.finance/coverage/ger30) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`1m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/ger30)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes**:

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **4H** · **12H** · **1D** · **3D** · **1W**

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples refreshed weekly, in sync with getdata.finance.

## Data preview

First and latest rows from the GitHub sample **`GER30_1m.csv`**:

**First rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-06-26T13:10:00+00:00 | 24614.64 | 24619.62 | 24605.62 | 24606.63 | 307 |
| 2026-06-26T13:11:00+00:00 | 24606.63 | 24613.63 | 24604.12 | 24608.12 | 362 |
| 2026-06-26T13:12:00+00:00 | 24608.12 | 24612.64 | 24605.64 | 24612.64 | 217 |
| 2026-06-26T13:13:00+00:00 | 24612.64 | 24617.12 | 24609.12 | 24616.13 | 197 |
| 2026-06-26T13:14:00+00:00 | 24616.13 | 24622.14 | 24612.13 | 24615.12 | 299 |

**Last rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-02T01:56:00+00:00 | 25835.26 | 25835.26 | 25824.28 | 25824.28 | 107 |
| 2026-09-02T01:57:00+00:00 | 25824.28 | 25824.78 | 25820.78 | 25820.78 | 99 |
| 2026-09-02T01:58:00+00:00 | 25820.78 | 25825.27 | 25820.78 | 25825.27 | 61 |
| 2026-09-02T01:59:00+00:00 | 25825.27 | 25829.76 | 25824.77 | 25827.77 | 88 |
| 2026-09-02T02:00:00+00:00 | 25827.77 | 25827.78 | 25825.76 | 25826.26 | 43 |

## Schema

| Column | Description |
| --- | --- |
| `time` | Bar open timestamp (UTC, ISO-8601). |
| `open` | Opening price of the candlestick bar. |
| `high` | Highest price during the bar. |
| `low` | Lowest price during the bar. |
| `close` | Closing price of the candlestick bar. |
| `volume` | Tick volume (number of price updates) during the bar. |

```text
time,open,high,low,close,volume
```

## Download full data

Full GER30 archive — 11 timeframes, gap-free, updated weekly:

**[-> Get the full GER30 dataset on getdata.finance](https://getdata.finance/datasets/ger30)**
