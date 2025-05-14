# zaturn

[Source Code](https://github.com/kdqed/zaturn)

## Description
Zaturn is an open-source MCP (Multi-Channel Processor) server that enables AI-powered data analysis and visualization across multiple data sources. It allows users to connect various databases and file formats, and then interact with their data using natural language queries, without having to write SQL or Python code. Zaturn processes queries, generates insights, and provides both textual and visual summaries of data.

## Features
- **Multiple Data Source Integration:**
  - Connects to SQL databases: PostgreSQL, SQLite, DuckDB, MySQL, ClickHouse
  - Supports file formats: CSV, Parquet
  - More connectors are planned for future releases
- **AI-Powered Natural Language Queries:**
  - Users can ask questions in plain English and receive instant analysis and insights
  - No need to write SQL or Python code
- **Visualizations:**
  - Generates image-based data visualizations (if supported by the client)
  - Supported plot types: Scatter plots, Line plots, Histograms, Strip plots, Box plots, Bar plots
  - If image rendering is not supported, plots are saved as files with the file location provided
- **Direct Data Querying:**
  - No need to upload data; queries data directly from databases or files, overcoming file size limitations of other AI tools
- **Easy Integration:**
  - Can be added to Claude Desktop or any MCP client
  - Configurable via command-line arguments or config files
- **Coherent Narrative Generation:**
  - Provides not just raw data but also narrative insights and suggestions
- **Open Source:**
  - Licensed under MIT
- **Roadmap Highlights:**
  - More data source connectors
  - Expanded visualization support
  - Predictive analytics and forecasting
  - Presentation and PDF generation
  - Native notebook interface

## Category
Data Analysis & Exploration MCP Servers

## Tags
- data-integration
- data-analysis
- ai-integration
- open-source

## Pricing
Zaturn is open-source and free to use. Voluntary support is encouraged via Patreon ($9/month), but there are no required paid plans.
