# dicom-mcp

**Category:** Data Access & Integration - MCP Servers  
**Source:** [GitHub Repository](https://github.com/christianhinge/dicom-mcp)

## Description
**dicom-mcp** is an MCP server that enables interaction with medical imaging systems using DICOM networking protocols. It allows AI assistants and other clients to query, retrieve, send, and parse medical images and encapsulated documents from DICOM servers such as PACS and VNA. It is intended for integration and development purposes, not for clinical use.

## Features
- **Query Metadata:** Retrieve metadata from DICOM servers.
- **Read DICOM Reports:** Extract and read encapsulated reports (e.g. PDFs) from DICOM servers.
- **Send DICOM Images:** Transfer DICOM images to and from DICOM servers.
- **Utilities:** Additional utility tools for DICOM data management and interaction.
- **Configurable:** Requires YAML-based configuration for defining DICOM nodes and AE titles.
- **Sample Server Integration:** Provides sample configuration for integration with ORTHANC DICOM server via Docker for testing and development.
- **MCP Integration:** Can be integrated with client applications via configuration files.
- **Development Tools:** Includes tools for testing (pytest) and debugging (MCP Inspector).
- **Not for Clinical Use:** Explicitly not intended for live hospital databases or sensitive patient data. Can be used with local open-weight LLMs for privacy.

## Pricing
No pricing information is provided. The project appears to be open source.

## Tags
`dicom` `medical-imaging` `data-access` `mcp`