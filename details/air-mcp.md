# Air MCP

[GitHub Source](https://github.com/binalyze/air-mcp)

**Category:** Security Attestation MCP Servers  
**Tags:** security, forensics, endpoint-management, integration

---

## Description

Air MCP is a Node.js server that implements the Model Context Protocol (MCP) for the Binalyze AIR digital forensics platform. It acts as a bridge between large language models (LLMs) and AIR, enabling natural language interaction with AIR's digital forensics and incident response functions. This allows users to manage endpoint security and forensics tasks without writing code or learning complex APIs.

---

## Features

- **Natural Language Interaction**: Enables users to interact with Binalyze AIR forensics and incident response via natural language commands through supported MCP clients.
- **Endpoint Management**: List, manage, and retrieve details about endpoints; assign tasks such as acquisition, reboot, shutdown, isolation, and log retrieval.
- **Acquisition Profiles and Artifacts**: List, create, update, and retrieve acquisition profiles and artifacts for evidence collection, organized by platform and category.
- **Evidence Management**: Assign acquisition and imaging tasks, list and manage evidence items, and export evidence data.
- **Case Management**: Create, update, archive, and manage cases; manage case notes, activities, endpoints, tasks, and associated users.
- **Task Management**: List, assign, update, cancel, and delete forensic and triage tasks; manage task assignments and retrieve detailed task information.
- **Policy Management**: Create, update, delete, and manage security and collection policies; view policy statistics and matches by platform and endpoint status.
- **Triage Rules and Tags**: List, create, update, validate, and delete triage rules and tags (YARA, OSQuery, Sigma) for threat detection.
- **Asset Tagging**: Create, update, list, and manage auto asset tag rules; start auto-tagging processes for assets based on conditions.
- **Baseline Acquisition and Comparison**: Acquire and compare baselines for endpoints and cases, and generate comparison reports.
- **E-discovery Patterns**: List available patterns for file type detection.
- **Evidence Repository Management**: Manage evidence repositories (SMB, SFTP, FTPS, Azure Storage, Amazon S3), including creation, validation, update, and deletion.
- **Audit Logs**: Export and list audit logs, including timestamp, user, action, and entity details.
- **Organization Management**: Create, update, and delete organizations; manage users and tags for organizations.
- **Webhook Integration**: Call and post to webhooks with specified data and tokens.
- **System Banner Message**: Update system-wide banner messages.
- **Authentication**: Requires an API token (via AIR_API_TOKEN environment variable) for secure access.

---

## Pricing

No pricing information is provided in the available content. Air MCP is open source and available on GitHub.
