<p align="center">
  <a href="#-buy-now">
    <img src="https://img.shields.io/badge/💰_BUY_NOW-Get_Full_Source_Code-success?style=for-the-badge&logo=bitcoin&logoColor=white" alt="Buy Now — Get Full Source Code">
  </a>
</p>

<div align="center">

# ⚡ Quantoo7 — Market Data & Quant Trading Infrastructure

### Historical + real-time market data for quants, algo traders, researchers, and developers.

**Looking for historical order-book data? Binance? Bybit? Deribit? NSE? IBKR? Stocks? Equity? Polymarket? Open interest, funding rates, trades, or candles?**  
Tell me the market, data type, time range, and format. I can provide **data, collection tools, or source code** depending on the request.


<p>
  <img src="https://img.shields.io/badge/Market_Data-Historical_%2B_Real--Time-00BFA6?style=for-the-badge" alt="Historical and real-time data">
  <img src="https://img.shields.io/badge/Formats-Parquet_%7C_CSV_%7C_JSON-3776AB?style=for-the-badge" alt="Data formats">
  <img src="https://img.shields.io/badge/Focus-Quant_%7C_Algo_%7C_HFT-7B61FF?style=for-the-badge" alt="Quant, algo and HFT">
</p>

<p>
  <a href="#-available-data"><strong>Available Data</strong></a> •
  <a href="#-supported-platforms"><strong>Platforms</strong></a> •
  <a href="#-how-to-order"><strong>How to Order</strong></a> •
  <a href="#-source-code-or-data"><strong>Source Code or Data</strong></a>
</p>

</div>

---

## 🔎 Are you looking for market data?

I help traders and developers source market data for **strategy research, backtesting, market microstructure analysis, execution research, and quantitative development**.

- 📚 **Historical data** for research and backtesting
- 📡 **Real-time data collection** where supported by the platform
- 📘 **Source code and collection pipelines** for supported datasets
- 🧪 **Order-book and trade data** for microstructure research
- 🗃️ **Structured exports** for analytics and storage

> **Need something specific?** Send the platform, market, symbols, data types, date range, and preferred file format by email. I’ll confirm feasibility and availability.

## 📊 Available Data

| Data type | What it contains | Typical use |
|---|---|---|
| 🕯️ **OHLCV / Candles** | Open, high, low, close, volume; supported intervals | Backtesting and signal research |
| 🥇 **L1 — Best bid/ask** | Top-of-book bid, ask, prices, and quantities where available | Spread and microprice analysis |
| 📚 **L2 — Order book depth** | Bid/ask price levels and quantities; configurable depth where supported | Order-book imbalance, liquidity, market making |
| ⚡ **Trades / AggTrades** | Trade price, quantity, timestamp, and available trade-side fields | Trade flow and execution analysis |
| 💸 **Funding rates** | Historical or current funding records where available | Perpetual futures research |
| 📈 **Open interest** | Open-interest observations where available | Derivatives and positioning research |
| 🧾 **Liquidations** | Liquidation events where available from the selected source | Liquidation-flow analysis |
| 🧰 **Custom datasets** | Other supported market endpoints or formats | Project-specific research |

**Availability depends on the platform, endpoint, retention limits, requested period, and collection method.** Not every platform exposes every data type historically. Historical L2 data in particular may have gaps or require data collected prospectively.

## 🗂️ Data Types & Availability

The table below summarises the data types that can be requested. **Availability is platform- and date-range-dependent**: ask before ordering to confirm historical coverage, granularity, and delivery format. A listed data type does not mean that every venue exposes it historically or that a complete archive is already available.

| Data type | Binance Spot | Binance USDⓈ-M Futures | Polymarket | Availability notes |
|---|---|---|---|---|
| 🕯️ OHLCV / Candles | ✅ Supported endpoints / configured intervals | ✅ Supported endpoints / configured intervals | ⚠️ Market-dependent price history | Interval and historical range must be confirmed |
| 🥇 L1 — Best bid/ask | ✅ | ✅ | ✅ | Real-time collection; historical snapshots depend on archived data |
| 📚 L2 — Order book depth | ✅ | ✅ | ✅ | Real-time collection; historical depth depends on archived data and requested depth |
| ⚡ Trades / AggTrades | ✅ Supported trade endpoints | ✅ Supported trade endpoints | ✅ Supported trade records where available | Fields and historical coverage vary by platform |
| 💸 Funding rates | N/A | ✅ Supported endpoint | N/A | Futures funding history is subject to endpoint limits |
| 📈 Open interest | N/A | ✅ Supported endpoint | N/A | Historical intervals and lookback limits vary |
| 🧾 Liquidations | N/A / endpoint-dependent | ⚠️ Endpoint- and collection-dependent | N/A / market-dependent | Confirm whether the required historical records are available |
| 🧩 Market metadata | ⚠️ Symbol / exchange metadata | ⚠️ Contract / exchange metadata | ✅ Market metadata where available | Fields differ by platform |
| 📦 Custom exports | ✅ Where source data exists | ✅ Where source data exists | ✅ Where source data exists | Parquet, CSV, JSON, or Excel where suitable |

**Legend:** ✅ Supported data type; ⚠️ confirm exact historical coverage before ordering; N/A means generally not applicable to that venue/data category.

### Availability by historical period

| Request type | Typical availability status |
|---|---|
| Historical candles and trades | Often available through platform history/endpoints, subject to retention and limits |
| Historical funding and open interest | Endpoint- and lookback-dependent; confirm requested dates |
| Historical L1/L2 order-book snapshots or updates | **Not guaranteed** for arbitrary past dates; depends on an existing archive or prospective collection |
| Real-time L1/L2 collection | May be arranged for supported markets and configured collectors |
| Polymarket historical order-book data | Coverage depends on the market, endpoint, archive, and requested time range |
| Custom dataset or format | Assessed individually before payment |

To check availability, email the **platform, market, symbol/market ID, data type, start/end dates, desired interval or depth, and output format**. Confirm the quote and coverage before paying.

## 🌐 Supported Platforms

<div align="center">

| Platform / venue | Potential data coverage |
|:--|:--|
| 🟡 **Binance Spot** | Candles, trades, L1/L2 collection, and other supported market endpoints |
| 🟡 **Binance USDⓈ-M Futures** | Candles, trades, funding, open interest, and supported derivatives data |
| 🔮 **Polymarket** | Market metadata, prices, trades, order-book snapshots, and supported CLOB data |
| 🔧 **Other platforms** | Ask about the venue and exact dataset you need |

</div>

<p align="center">
  <img src="i/binance-dashboard.png" alt="Binance data pipeline screenshot" width="48%">
  <img src="i/orderbook.png" alt="Order book data sample" width="48%">
</p>
<p align="center">
  <em>Replace the image paths above with screenshots you choose to publish.</em>
</p>

More venues and data types can be discussed on request. Coverage is confirmed **per request**; this page is not a claim that every dataset is already stored or available for immediate delivery.

## 🧱 Data Formats

Choose the format that best fits your workflow:

- **Parquet** — columnar storage for large datasets and analytics
- **CSV** — convenient for quick inspection and broad tool compatibility
- **JSON / JSONL** — structured records and event data
- **Excel** — conversion or exports for smaller datasets, where practical

For large order-book datasets, **Parquet is generally recommended** because it is compact and works well with tools such as Python, Polars, and PyArrow.

## 🖥️ Data Pipeline & Tooling

This repository may include tools for collecting, processing, storing, and converting market data.

<p align="center">
  <img src="i/config-summary.png" alt="Data pipeline configuration summary" width="48%">
  <img src="i/cli-menu.png" alt="Market data CLI menu" width="48%">
</p>

Example capabilities, depending on the version and configured exchange:

- Historical candle backfills
- WebSocket-based market-data ingestion
- Configurable L2 depth collection
- Parquet-based storage
- CLI-driven symbol and data-type selection
- Data conversion and analysis workflows

### Example: run a historical backfill

```bash
python src/cli.py backfill \
  --start 2026-07-01 \
  --end 2026-07-15 \
  --config config/symbols_test.yaml
```

Example symbol configuration:

```yaml
symbols:
  - symbol: BTCUSDT
    market: spot
    data_types:
      - candles_1s
```

Check the current code and configuration before running commands; options and supported data types may vary by version.

---

---

# 📸 Output Screenshots & Sample Data

Explore sample outputs from the Quantoo7 Crypto Market Data Pipeline.

## 📊 1. L2 Order Book — Best Bid & Ask

Sample L2 order book data exported to Excel.

![L2 Order Book Excel Output](./sample%20L2%20output%20excel%20best%20bid%20ask.png)

---

## 📈 2. L2 Order Book — Market Depth Snapshot

Snapshot of collected Level 2 order book data.

![L2 Order Book Data Snapshot](./L2%20orderbook%20data%20snapshot.jpeg)

---

## 💻 3. Terminal Output — Pipeline Execution

Terminal output showing the market data pipeline in action.

![Market Data Pipeline Terminal Output](./terminal%20output%20selection%20ss.png)

---

## ⚡ 4. BTCUSDT — Historical Backfill

Terminal command for historical BTCUSDT data collection.

![BTCUSDT Historical Backfill Terminal](./btcusdt%201s%20historical%20backfill%20terminal%20command%20ss.png)

---

## ⚙️ 5. Historical Backfill — YAML Configuration

Example YAML configuration for selecting symbols and data types.

![Historical Backfill YAML Configuration](./btcusdt%201s%20historical%20backfill%20yaml%20file%20ss.png)

---

---

## 💻 Source Code or Data?

Choose the option that suits your project:

### Option A — Request a dataset
Tell me exactly what data you need. If it is available and can be provided, I’ll confirm the scope, format, and price before delivery.

### Option B — Request source code
Need a collector, conversion utility, data pipeline, or custom implementation? Describe your use case and required platform. Source code availability and licensing are agreed individually.

### Option C — Request a custom dataset
For larger requests, include the symbols, market, data types, time range, depth, update frequency, and storage format.

**No claim of profitability is made for any strategy or trading system.** Market data and software are supplied for research and development; trading decisions and risk remain your responsibility.

---

## 📨 Buy Source Code or Request Custom Work

### ⚡ Direct Source Code Purchase — $100

Want to buy the available source code directly?

**Price: $100 USD**  
**BTC amount: 0.0012 BTC** *(confirm the exact amount before payment, as BTC prices fluctuate)*

1. Send the payment to the Bitcoin address below.
2. Email your order to **`hex_user_0x1@proton.me`**.
3. Put the **Bitcoin transaction hash (TXID) in the email subject**.

**BTC payment address:** `bc1qzf6dqpguyxnajuq6t3tulwtk7jsaprmjajeqjq`

<a id="-buy-now"></a>

# 💰 Buy Now

**Get the complete Quantoo7 Crypto Market Data Pipeline source code.**

- **Price:** $100 USD
- **Payment:** Bitcoin (BTC)

Contact: YOUR_EMAIL@example.com

Use this email subject format:

```text
SOURCE CODE PURCHASE | TXID: your_transaction_hash
```

No transaction hash in the subject means the automated workflow may reject or fail to process the email.

After **3 blockchain confirmations** and successful payment verification, the source code is intended to be delivered automatically to your email inbox **within 10 minutes**.

> Automated delivery depends on the payment-verification and email-delivery systems being operational. Only use this purchase flow once it has been configured and tested.

### 🛠️ Need Something Custom?

For custom data collection, a different exchange or market, additional data types, a specific historical period, a different output format, or custom development, email:

**`hex_user_0x1@proton.me`**

Include the details below so the request can be assessed:

```text
Platform / Exchange:
Market:
Symbol(s) / Market ID:
Data type:
Date range / duration:
L2 depth, if applicable:
Preferred format:
Source code or dataset:
Custom requirements:
Budget / deadline (optional):
```

Custom requests will be reviewed separately, and availability, scope, price, and delivery time will be confirmed by email before payment.

## ⚠️ Important Notes

- **Availability first:** historical coverage differs by venue and endpoint. Confirm before paying.
- **Historical L2 limitations:** many exchanges do not provide complete historical order-book updates for arbitrary past dates. Some requests may only be possible from previously archived data or from collection started now.
- **No guaranteed returns:** data, source code, and research tools do not guarantee profitable trading.
- **Licensing and redistribution:** data access, redistribution, and commercial use are subject to the source platform’s terms and applicable law. The buyer is responsible for confirming that their intended use is permitted.
- **Security:** never email private keys, seed phrases, exchange API secrets, or wallet credentials.
- **Professional background:** any employment or HFT affiliation mentioned in a profile should be accurate and must not disclose confidential employer information.

## 🤝 Contact

For dataset availability, source code, custom collection, or commercial licensing:

- **Email:** `hex_user_0x1@proton.me`
- **GitHub:** [@quantoo7](https://github.com/quantoo7)

<div align="center">

### ⚡ Need market data for your next quant project?

**Send the platform + market + data type + date range + format.**

<sub>Quantoo7 · Market Data · Quantitative Research · Trading Infrastructure</sub>

</div>
