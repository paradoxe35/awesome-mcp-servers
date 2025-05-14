# Dvmcp

Dvmcp is a deliberately vulnerable Model Context Protocol (MCP) server designed for security researchers and developers to test and learn about AI/ML model serving vulnerabilities. It is intended strictly for educational and research purposes and should **not** be used in production environments.

## Features
- **Deliberately Vulnerable MCP Server**: Implements a wide range of intentional vulnerabilities for hands-on security research.
- **Model Context Manipulation**: Allows unrestricted modification of model context and system prompts.
- **Prompt Injection**: Unsanitized prompt handling and context contamination vulnerabilities.
- **Model Access Control Bypass**: Weak access controls and capability validation, allowing for bypass exploits.
- **Model Chain Attacks**: Permits unrestricted model chaining and context persistence vulnerabilities.
- **Response Manipulation**: Susceptible to template injection and system information exposure.
- **Rate Limit Bypassing**: Ineffective rate limiting implementation.
- **System Prompt Exposure**: Unprotected access and modification of system prompts.
- **Model Capability Enumeration**: Excessive information disclosure about model capabilities.
- **Educational Documentation**: Includes guides on exploitation, deployment, and client integration.
- **MIT Licensed**: Open source under the MIT License.

## Category
Reference Implementations & Examples

## Tags
security, testing, example, mcp

## Source
[https://github.com/Karanxa/dvmcp](https://github.com/Karanxa/dvmcp)

## Pricing
Dvmcp is open source and available free of charge under the MIT License.