# johnneerdael/netskope-mcp

**Repository:** [johnneerdael/netskope-mcp on GitHub](https://github.com/johnneerdael/netskope-mcp)

**Category:** cloud-devops-mcp-servers

**Tags:** mcp, netskope, cloud, llm

## Description
A Model Context Protocol (MCP) server for managing Netskope Network Private Access (NPA) infrastructure through Large Language Models (LLMs). Provides access to all Netskope Private Access components within Netskope environments, including detailed setup and LLM examples.

**Note:** The project is under development and is not recommended for production use as all 50 tools are not yet fully operational.

## Features
- **MCP Server for Netskope NPA**: Manage Netskope Network Private Access infrastructure via LLMs.
- **Multiple Installation Methods**: Available as an npm package or for local development.
- **Environment Variable Configuration**: Requires `NETSKOPE_BASE_URL` and `NETSKOPE_API_KEY`.
- **Component Access and Management Tools**:
  - **AlertsTools**:
    - getAlertConfig
    - updateAlertConfig
  - **LocalBrokerTools**:
    - listLocalBrokers
    - createLocalBroker
    - getLocalBroker
    - updateLocalBroker
    - deleteLocalBroker
    - getBrokerConfig
    - updateBrokerConfig
    - generateLocalBrokerRegistrationToken
  - **PolicyTools**:
    - listRules
    - getRule
    - createRule
    - updateRule
    - deleteRule
  - **PrivateAppsTools**:
    - createPrivateApp
    - updatePrivateApp
    - deletePrivateApp
    - getPrivateApp
    - listPrivateApps
    - getPrivateAppTags
    - createPrivateAppTags
    - updatePrivateAppTags
    - updatePrivateAppPublishers
    - deletePrivateAppPublishers
    - getDiscoverySettings
    - getPolicyInUse
  - **PublishersTools**:
    - listPublishers
    - getPublisher
    - createPublisher
    - patchPublisher
    - updatePublisher
    - deletePublisher
    - bulkUpgradePublishers
    - getReleases
    - getPrivateApps
    - generatePublisherRegistrationToken
  - **UpgradeProfileTools**:
    - listUpgradeProfiles
    - getUpgradeProfile
    - createUpgradeProfile
    - updateUpgradeProfile
    - deleteUpgradeProfile
  - **SteeringTools**:
    - updatePublisherAssociation
    - deletePublisherAssociation
    - getUserDiagnostics
    - getDeviceDiagnostics
  - **ValidationTools**:
    - validateName
    - validateResource
    - searchResources
- **Demo video available**: [demo.mov](https://github.com/johnneerdael/netskope-mcp/raw/refs/heads/main/demo.mov)

## Installation
- **NPM Package:** Install via npm.
- **Local Development:** Clone repository and install dependencies.
- **Platform Support:** Instructions for Windows (with WSL), Linux, and macOS.

## Requirements
- Environment variables: `NETSKOPE_BASE_URL`, `NETSKOPE_API_KEY`.

## Pricing
No pricing information is provided; the project is open source on GitHub.