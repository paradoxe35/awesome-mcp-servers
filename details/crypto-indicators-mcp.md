# crypto-indicators-mcp

An MCP server delivering real-time technical analysis indicators and trading signals for cryptocurrency markets, useful for MCP-based quantitative strategy development and trading automation.

- **Source:** [GitHub Repository](https://github.com/kukapay/crypto-indicators-mcp)
- **Category:** blockchain-crypto-mcp-servers
- **Tags:** mcp, crypto, market-data, real-time, trading

---

## Features

- **Range of Technical Indicators:**
  - 50+ indicators across trend, momentum, volatility, and volume categories.
  - Indicators include: Absolute Price Oscillator, Aroon, Balance of Power, CCI, DEMA, EMA, MACD, Parabolic SAR, KDJ, SMA, TEMA, TRIX, VWMA, Vortex, Awesome Oscillator, Ichimoku Cloud, RSI, Stochastic Oscillator, Williams %R, Bollinger Bands, ATR, Chandelier Exit, Keltner Channel, Donchian Channel, Ulcer Index, Accumulation/Distribution, Chaikin Money Flow, Ease of Movement, Force Index, Money Flow Index, NVI, OBV, VPT, VWAP, and more.

- **Trading Strategies:**
  - Corresponding trading strategies outputting signals: -1 (SELL), 0 (HOLD), 1 (BUY).
  - Strategies include: APO, Aroon, BOP, CFO, KDJ, MACD, PSAR, VWMA, Vortex, AO, Ichimoku, RSI, Stochastic, Williams %R, Acceleration Bands, Bollinger Bands, Projection Oscillator, CMF, EMV, FI, MFI, NVI, VWAP, and generic momentum strategies.

- **Flexible Data Source:**
  - By default uses Binance as data source.
  - Configurable to any exchange supported by `ccxt`.

- **Modular Design:**
  - Indicators and strategies are categorized for easier maintenance and extension.

- **Empowers AI Trading Agents:**
  - Designed to support AI-driven trading and quantitative research via MCP protocol.

- **Installation Requirements:**
  - Node.js (v18.x or higher) and npm (v8.x or higher).

- **Open Source:**
  - Licensed under MIT license.

## Usage Examples

- **Calculate MACD Indicator:**
  - Input: "Calculate the MACD for BTC/USDT on a 1-hour timeframe with fast period 12, slow period 26, signal period 9, and fetch 100 data points."
  - Output: `{ "macd": [...], "signal": [...], "histogram": [...] }`

- **Calculate RSI Strategy:**
  - Input: "Give me the RSI strategy signals for ETH/USDT on a 4-hour timeframe with a period of 14 and 50 data points."
  - Output: `[-1, 0, 1, 0, ...]`

## Pricing

- **Open Source / Free:**
  - The project is open source under the MIT license. No paid plans or commercial pricing are listed.

## License

- MIT License
