# Custom Context MCP

[Source Code](https://github.com/omer-ayhan/custom-context-mcp)

## Category
Development Tools – MCP Servers

## Description
Custom Context MCP is a Model Context Protocol (MCP) server designed to transform unstructured text into structured JSON data using customizable templates with placeholders. It supports integration within MCP server ecosystems and provides tools for structuring and extracting data from text based on JSON templates.

## Features
- **Text-to-JSON Transformation:** Transforms unstructured text into structured JSON using templates.
- **Group Text by JSON (group-text-by-json):**
  - Accepts a JSON template with placeholders.
  - Generates an AI prompt to group text according to the template's structure.
  - Extracts placeholder keys from the template and creates a prompt for AI to extract information in key-value format.
- **Text to JSON (text-to-json):**
  - Converts grouped text (from the previous tool) into a structured JSON object.
  - Extracts key-value pairs from text and structures them as per the original template.
- **Flexible Template Format:**
  - Supports placeholders anywhere within valid JSON structures, including nested placeholders.
- **Custom Hot Reloading for Development:**
  - Includes a custom hot reloading setup for efficient development workflow.
- **MCP Inspector Integration:**
  - Can be used with MCP Inspector for visual debugging of requests and responses.

## Pricing
No pricing information provided. The project appears to be open source.

## Tags
mcp, context-management, template, json