# automated-bod-25-01-cisa-microsoft-policies-mcp

**Category:** security-attestation-mcp-servers  
**Tags:** mcp, security, compliance, microsoft-365  
**Source:** [GitHub Repository](https://github.com/dynamicendpoints/automated-bod-25-01-cisa-microsoft-policies-mcp)

## Description
A Model Context Protocol (MCP) server that enforces CISA Binding Operational Directive 25-01 security controls for Microsoft 365 (Azure AD/Entra ID) environments. It integrates with the Microsoft Graph API to automate policy management, compliance monitoring, and reporting for Microsoft 365 security configurations.

## Features
- **Automated Enforcement of CISA BOD 25-01 Controls**: Implements required security controls for Microsoft 365, including:
  - Block legacy authentication (MS.AAD.1.1v1)
  - Block high-risk users and sign-ins (MS.AAD.2.1v1 & MS.AAD.2.3v1)
  - Enforce and configure MFA (MS.AAD.3.1v1, MS.AAD.3.2v1, MS.AAD.3.3v1)
  - Application controls (MS.AAD.5.1v1 - MS.AAD.5.4v1)
  - Password policy enforcement (MS.AAD.6.1v1)
  - Privileged role management (MS.AAD.7.1v1 - MS.AAD.7.8v1)
- **Integration with Microsoft Graph API**: Uses Graph API for direct policy management and status retrieval.
- **Compliance Monitoring**: Monitors and reports on the compliance status of all enforced policies.
- **API Tools and Endpoints**:
  - block_legacy_auth: Block legacy authentication methods
  - block_high_risk_users: Block high-risk users
  - enforce_phishing_resistant_mfa: Ensure phishing-resistant MFA is enabled
  - configure_global_admins: Manage global admin role assignments
  - get_policy_status: Retrieve current status of all security policies
- **Comprehensive Error Handling**: Handles authentication, API, validation, and runtime errors with structured responses.
- **Extensible Architecture**: Modular components including server class, authentication, Graph client, and tools.
- **Installation via Smithery**: Can be installed and configured automatically using Smithery or manually.
- **Security Considerations**: Focuses on authentication, API access, and data protection.
- **Open Source**: Licensed under MIT.

## Pricing
No pricing information is provided; the project is open source under the MIT license.

## Resources
- [GitHub Repository](https://github.com/dynamicendpoints/automated-bod-25-01-cisa-microsoft-policies-mcp)