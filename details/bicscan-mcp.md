# bicscan-mcp

BICScan MCP Server is an open-source MCP (Model Context Protocol) server that provides risk scoring and asset holding analysis for EVM blockchain addresses, including EOAs, contracts, ENS, and domains. It leverages the BICScan API for comprehensive risk assessments and asset information.

- **Source:** [GitHub Repository](https://github.com/ahnlabio/bicscan-mcp)
- **Category:** blockchain-crypto-mcp-servers
- **Tags:** evm, blockchain, risk-analysis, open-source

## Features
- **Risk Scoring:**
  - Provides risk scores (0-100, where 100 is high risk) for blockchain entities: crypto addresses, domain names, and dApp URLs.
- **Asset Information:**
  - Retrieves detailed asset holdings for specified addresses, including cryptocurrencies and tokens, across multiple blockchain networks.
- **Real-time Scanning:**
  - Utilizes the BICScan API to perform real-time scans and deliver up-to-date information on risks and asset holdings.
- **Secure and Reliable:**
  - Robust error handling and logging ensure secure and reliable server operation.
- **Multiple Deployment Options:**
  - Can be run using Python (with uv or uvx) or Docker.
- **Integration:**
  - Officially listed for integration in Model Context Protocol (MCP) server registries.

## Installation & Usage
- **Requirements:**
  - Python 3.10+
  - uv 0.6.x (for Python usage)
  - Docker (for containerized deployment)
  - BICScan API key (free, obtainable from [bicscan.io](https://bicscan.io))
- **Deployment Methods:**
  - Run with `uv`, `uvx` (Python), or Docker.
  - Configuration instructions are available in the repository README.

## Pricing
- **API Key:**
  - A free API key can be obtained by registering at [bicscan.io](https://bicscan.io). No paid plans or pricing details are specified.

## License
- MIT License

---
For full documentation and setup instructions, visit the [GitHub repository](https://github.com/ahnlabio/bicscan-mcp).