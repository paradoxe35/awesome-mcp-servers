# genai-toolbox

[Source Code](https://github.com/googleapis/genai-toolbox)

## Description
Gen AI Toolbox for Databases is an open source server designed to simplify the development of Gen AI tools that interact with databases. It handles complexities such as connection pooling and authentication, enabling easier, faster, and more secure tool development and management.

## Features
- **Open Source Server**: Enables building Gen AI tools for database interaction.
- **Simplified Development**: Integrate tools into agents with minimal code and reuse tools across multiple agents or frameworks.
- **Performance Optimization**: Implements best practices like connection pooling and authentication for improved performance.
- **Enhanced Security**: Integrated authentication for secure data access.
- **End-to-End Observability**: Built-in metrics and tracing with support for OpenTelemetry.
- **Centralized Tool Management**: Control plane to modify, distribute, and invoke tools, allowing sharing and updating tools between agents and applications without redeployment.
- **Flexible Installation**: Can be installed as a binary, container image, or compiled from source.
- **Extensive Configuration**: Uses a `tools.yaml` file to define data sources, tools, and toolsets.
- **Client SDK Support**: Provides SDKs for integration with frameworks like LangChain and LangGraph.
- **Semantic Versioning**: Follows MAJOR.MINOR.PATCH versioning for releases.

## Usage
- Define data sources, tools, and toolsets in a YAML configuration file.
- Install and run the server as a binary, container, or from source.
- Integrate with applications using provided SDKs (e.g., LangChain SDK for Python).

## License
Apache-2.0

## Pricing
Open source and free to use.