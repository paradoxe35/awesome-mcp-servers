# aws-mcp-server

A lightweight MCP server that allows AI assistants (such as Claude Desktop, Cursor, and other MCP-aware tools) to execute AWS CLI commands, use Unix pipes, and apply prompt templates for AWS tasks in a secure, multi-architecture Docker environment.

- **Source:** [https://github.com/alexei-led/aws-mcp-server](https://github.com/alexei-led/aws-mcp-server)
- **Category:** cloud-devops-mcp-servers
- **Tags:** aws, cloud, mcp, docker

---

## Features

- **Bridges AI Assistants and AWS CLI:** Enables MCP-aware AI assistants to execute AWS CLI commands in a safe, containerized environment.
- **Multi-Architecture Docker Support:** Official Docker image supports AMD64/x86_64 and ARM64 architectures (Intel/AMD, Apple Silicon, AWS Graviton).
- **Unix Pipe Support:** Allows use of Unix pipes in command execution.
- **Prompt Templates:** Includes a wide range of pre-defined prompt templates for AWS operations, such as:
  - Core operations (create_resource, resource_inventory, troubleshoot_service, resource_cleanup)
  - Security & Compliance (security_audit, iam_policy_generator, compliance_check)
  - Cost & Performance (cost_optimization, performance_tuning)
  - Infrastructure & Architecture (serverless_deployment, container_orchestration, vpc_network_design, infrastructure_automation, multi_account_governance)
  - Reliability & Monitoring (service_monitoring, disaster_recovery)
- **Flexible Deployment:** Can be run via Docker (recommended) or natively via Python.
- **Configurable Environment:** Supports configuration via environment variables for timeouts, output size, transport protocol, AWS profile/region, and security modes.
- **Comprehensive Security:**
  - Multi-layered command validation system
  - Default blocklists for high-risk AWS CLI commands (IAM, audit/logging, sensitive data, network risks)
  - Custom security rules via YAML configuration
  - Strict and permissive security modes
  - Follows IAM least-privilege best practices
- **Integration with Claude Desktop and other MCP tools:** Provides detailed instructions for integration and usage.
- **Command Execution Controls:** Limits execution time and output size; validates command structure and usage.
- **Development and Testing:** Includes Makefile for common development tasks, integration tests, and code coverage reporting via Codecov.
- **Versioning:** Uses setuptools_scm for automatic version management based on Git tags.
- **Open Source:** Licensed under the MIT License.

---

## Security Considerations

- Docker deployment is strongly recommended for security and reliability.
- Requires careful management of AWS credentials (principle of least privilege).
- Default blocklists prevent execution of high-risk AWS CLI operations.
- Supports custom security configurations and strict/permissive security modes.

---

## Requirements

- Docker (recommended) or Python environment
- AWS credentials with appropriate permissions (least privilege)

---

## Pricing

No pricing information provided; aws-mcp-server is open source and licensed under the MIT License.

---

## License

MIT License
