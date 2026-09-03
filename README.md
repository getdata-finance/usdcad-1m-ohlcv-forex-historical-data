# USDCAD 1m OHLCV Forex Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-9_146_902_rows-blue)](https://getdata.finance/datasets/usdcad) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/usdcad)

### -> [**Download the full USDCAD dataset on getdata.finance**](https://getdata.finance/datasets/usdcad)

**USDCAD 1m OHLCV forex historical data** — ultra high-quality 1m OHLCV for **US Dollar / Canadian Dollar**. Clean `time, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 1m OHLCV** for **US Dollar / Canadian Dollar** (Forex)
- **Clean CSV schema** — `time, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1m`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/usdcad) · **9,146,902** `1m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `1m` sample updated in sync

> **Sample on GitHub** · `USDCAD_1m.csv` (55,440 rows, `2026-07-09` -> `2026-09-02`). **Full archive on [getdata.finance](https://getdata.finance/datasets/usdcad)** — **9,146,902** `1m` rows, **11 timeframes**, `2001-11-28` -> `2026-09-02`.

## Download sample

**[USDCAD_1m.csv](https://github.com/getdata-finance/usdcad-1m-ohlcv-forex-historical-data/blob/main/USDCAD_1m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/usdcad-1m-ohlcv-forex-historical-data/main/USDCAD_1m.csv))

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/usdcad))** |
|---|--:|---|
| Instrument | US Dollar / Canadian Dollar · Forex | US Dollar / Canadian Dollar · Forex |
| Timeframes | `1m` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 1m rows | 55,440 | **9,146,902** |
| Period | `2026-07-09` -> `2026-09-02` | `2001-11-28` -> `2026-09-02` |
| File | `USDCAD_1m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/usdcad) |
| Coverage report | — | [USDCAD coverage](https://getdata.finance/coverage/usdcad) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`1m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/usdcad)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes**:

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **4H** · **12H** · **1D** · **3D** · **1W**

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples refreshed weekly, in sync with getdata.finance.

## Data preview

First and latest rows from the GitHub sample **`USDCAD_1m.csv`**:

**First rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-07-09T13:08:00+00:00 | 1.41605 | 1.41606 | 1.41595 | 1.41596 | 158 |
| 2026-07-09T13:09:00+00:00 | 1.41596 | 1.41603 | 1.41586 | 1.41599 | 114 |
| 2026-07-09T13:10:00+00:00 | 1.41599 | 1.41602 | 1.41599 | 1.41601 | 78 |
| 2026-07-09T13:11:00+00:00 | 1.41601 | 1.41612 | 1.41598 | 1.4161 | 119 |
| 2026-07-09T13:12:00+00:00 | 1.4161 | 1.41621 | 1.41607 | 1.41621 | 96 |

**Last rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-02T01:56:00+00:00 | 1.39014 | 1.39022 | 1.39013 | 1.39021 | 39 |
| 2026-09-02T01:57:00+00:00 | 1.39021 | 1.39023 | 1.39018 | 1.3902 | 111 |
| 2026-09-02T01:58:00+00:00 | 1.3902 | 1.39026 | 1.39015 | 1.39023 | 171 |
| 2026-09-02T01:59:00+00:00 | 1.39023 | 1.39024 | 1.39013 | 1.39015 | 158 |
| 2026-09-02T02:00:00+00:00 | 1.39015 | 1.39039 | 1.39014 | 1.39036 | 140 |

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

Full USDCAD archive — 11 timeframes, gap-free, updated weekly:

**[-> Get the full USDCAD dataset on getdata.finance](https://getdata.finance/datasets/usdcad)**
