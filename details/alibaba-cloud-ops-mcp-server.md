# alibaba-cloud-ops-mcp-server

**Description:**
A server for managing and operating resources on Alibaba Cloud, supporting ECS, Cloud Monitor, OOS, and other Alibaba Cloud products via the MCP protocol.

**Source:** [GitHub Repository](https://github.com/aliyun/alibaba-cloud-ops-mcp-server)

## Features
- **Supports Multiple Alibaba Cloud Products:**
  - ECS (Elastic Compute Service)
    - RunCommand: Execute commands (via OOS)
    - Start/Stop/Reboot Instances (via OOS)
    - View Instances, Regions, Zones, Available Resources, Images, Security Groups (via API)
    - Create/Delete/Reset Password/Replace System Disk for Instances (via OOS/API)
  - VPC (Virtual Private Cloud)
    - View VPCs and VSwitches (via API)
  - RDS (Relational Database Service)
    - List, Start, Stop, and Restart RDS Instances (via API/OOS)
  - OSS (Object Storage Service)
    - List/Create/Delete Buckets, View objects in buckets (via API)
  - CloudMonitor
    - Retrieve metrics for ECS instances:
      - CPU Usage, 1/5/15-minute Load Average
      - Memory Usage and Utilization
      - Disk Usage, Total Capacity, Partition Usage
- **MCP Protocol:** Operate resources via the MCP protocol, enabling automation and integration with other MCP clients.
- **Out of the Box:** Ready to use with simple configuration.
- **Configuration:**
  - Customizable via JSON configuration (supports environment variables for Alibaba Cloud credentials).
  - Can be integrated with VS Code + Cline or other MCP Clients.
- **Implementation:**
  - Most tools are implemented either via Alibaba Cloud API or OOS (Operation Orchestration Service).
- **Open Source:**
  - Licensed under Apache-2.0.
  - Written in Python.

## Pricing
No pricing information is provided; the project is open source under the Apache-2.0 license.

## Tags
`mcp` `cloud` `alibaba-cloud` `automation`