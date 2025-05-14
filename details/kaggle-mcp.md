# kaggle-mcp

**Category:** Data Access Integration MCP Servers  
**Tags:** mcp, data-access, datasets, kaggle, analysis  
**Source:** [GitHub - arrismo/kaggle-mcp](https://github.com/arrismo/kaggle-mcp)

---

## Overview
**kaggle-mcp** is an open-source MCP (Model Context Protocol) server that integrates with Kaggle, allowing programmatic search, download, and analysis of Kaggle datasets. It is built using the fastmcp library and is intended for use with MCP-compatible clients, agents, or AI models.

---

## Features
- **Kaggle Dataset Search:**
  - Provides a tool `search_kaggle_datasets(query: str)` to search Kaggle for datasets matching a query string.
  - Returns a list of up to 10 top matching datasets, including metadata such as reference, title, download count, and last updated date.

- **Dataset Download:**
  - Tool `download_kaggle_dataset(dataset_ref: str, download_path: str | None = None)` enables downloading and unzipping of specific Kaggle datasets.
  - Supports specifying a download path; defaults to a `datasets/` directory if not provided.

- **EDA Notebook Prompt Generation:**
  - Tool `generate_eda_notebook(dataset_ref: str)` produces a prompt for an AI model to generate an Exploratory Data Analysis (EDA) notebook for a given dataset.
  - The prompt includes instructions for data loading, missing value checks, visualizations, and basic statistics.

- **Integration:**
  - Can be used as an MCP server by MCP clients or AI agents.
  - Example configuration provided for integration with Claude Desktop.

- **Environment variable and credential setup:**
  - Supports configuration via `.env` file or `kaggle.json` API credentials.

- **Docker Support:**
  - Includes a Dockerfile for containerized deployment.

---

## Technical Notes
- Built with Python (fastmcp library).
- Requires Kaggle API credentials to access datasets.
- Project structure includes server application, example environment file, dependency files, and a default datasets directory.
- Licensed under the MIT License.

---

## Pricing
This is a free and open-source project (MIT License). No pricing plans are required.
