# finData-mcp-server

[Source Code](https://github.com/zlinzzzz/finData-mcp-server)

## Overview
finData-mcp-server is an open-source Model Context Protocol (MCP) server that provides professional-level financial data access from multiple providers, such as Tushare, Wind, and Allin (通联). It is designed to supply large language models and AI applications with quick access to financial data.

## Features
- **Multi-provider Support**: Access financial data from various providers. Currently, Tushare is supported via environment configuration (`PROVIDER` environment variable).
- **Professional Financial Data Access**: Enables AI applications to fetch a wide range of financial data through a unified API.
- **Extensible Toolset (Tushare tools)**:
  - **Market Data**:
    - `daily`: Fetch daily stock price data (unadjusted).
  - **Basic Data**:
    - `stock_basic`: Retrieve basic information such as stock name and code.
    - `stock_company`: Get fundamental information about listed companies.
    - `bak_basic`: Obtain basic stock data over a specified time range.
  - **Financial Data**:
    - `income`: Access company income statement data.
    - `balancesheet`: Access balance sheet data.
    - `cashflow`: Access cash flow data.
  - **Macroeconomic Data**:
    - `shibor_lpr`: Get LPR (Loan Prime Rate) data.
    - `cn_gdp`: Retrieve GDP data.
    - `cn_cpi`: Consumer Price Index data.
    - `cn_ppi`: Producer Price Index data.
    - `cn_m`: Money supply data.
    - `sf_month`: Social financing data.
    - `cn_pmi`: Purchasing Managers' Index data.
- **Open Source**: Licensed under Apache-2.0.
- **Python-based**: Implemented in Python, requires Python >=3.11.
- **MCP CLI Compatible**: Requires `mcp[cli]>=1.6.0`, `pandas>=2.2.3`, and provider-specific packages (e.g., `tushare>=1.4.21`).

## Supported Data Providers
- Tushare (currently implemented)
- Wind (configurable, not detailed in the content)
- Allin/通联 (configurable, not detailed in the content)

## Pricing
- Open source and free to use under the Apache-2.0 license.

## Category
- data-access-integration-mcp-servers

## Tags
- finance, data-access, integration, mcp
