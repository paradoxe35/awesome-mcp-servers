# esa

[Source Code](https://github.com/aliyun/mcp-server-esa)

## Description
esa is an implementation of the Model Context Protocol (MCP) server that enables AI models to communicate with Edge Security Acceleration (ESA) services. It manages routines, deployments, and other resources using standardized protocols, acting as a bridge between AI models and ESA features.

## Category
cloud-devops-mcp-servers

## Tags
mcp, cloud, automation, edge

## Features
- **Routine Management**
  - Create, delete, list, and get details of routines
  - Commit and deploy routine code with support for versioning and environments (production/staging)
  - Canary deployment support with area management
- **Deployment Tools**
  - Manage routine deployments, including code commit and deploy
  - Delete deployments
  - List available canary areas
- **Route Management**
  - Create, update, delete, and get routine routes
  - Support for both simple and custom route modes
  - Enable/disable routes, set bypass, and sequence
  - List all routes for a routine or a site, with pagination and filtering
- **Record Management**
  - Create, delete, and list records for routines and sites
  - Support for searching and pagination
- **Site Tools**
  - List all active sites
  - Match sites under the account based on user input
  - DNS management: create A and CNAME records for sites
  - List all DNS records in a site

## Installation
- Configure in your MCP-enabled client configuration.

## License
ISC

## Pricing
No pricing information provided; open-source under the ISC license.