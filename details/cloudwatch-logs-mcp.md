# Cloudwatch Logs MCP

A Python-based MCP (Model Context Protocol) server that provides direct access to AWS CloudWatch logs. This server allows AI assistants and other clients to interact with CloudWatch for log management tasks.

## Features
- **List CloudWatch Log Groups**: Provides a tool to list available CloudWatch log groups, returning details such as `logGroupName`, `creationTime`, and `storedBytes`.
- **Retrieve Log Entries**: Allows fetching log events from a specific log group, returning details like `timestamp`, `message`, and `logStreamName`.
- **Async Tool Implementation**: Tools are implemented as async functions for efficient performance.
- **Built on FastMCP and boto3**: Uses the FastMCP class from the MCP SDK for server implementation and boto3 for AWS API interactions.
- **Docker Support**: Can be run in a Docker container for easy deployment.
- **AWS Credentials Support**: Requires AWS credentials, which can be configured via AWS CLI or environment variables.
- **Integration with AI Assistants**: Example provided for integration with Claude Desktop via configuration file.
- **Open Source (MIT License)**: Code is open source and available under the MIT license.

## Pricing
No pricing information provided. The project is open source and free to use.

## Source
[Cloudwatch Logs MCP on GitHub](https://github.com/serkanh/cloudwatch-logs-mcp)