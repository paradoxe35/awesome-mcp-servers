# AI Expert Workflow MCP

**Category:** ai-integration-mcp-servers  
**Tags:** mcp, ai-integration, workflow, automation, product-development

## Overview
AI Expert Workflow MCP is an open-source MCP (Model Context Protocol) server that enables structured product development through specialized AI roles. It uses the OpenRouter API for AI capabilities and facilitates the conversion of requirements into actionable tasks. The project can operate standalone or integrate with Task Master for task management.

## Features
- **Structured Product Development Workflow:** Implements a guided, conversational process for product planning and development.
- **Three Spheres Method:** Follows a phased approach:
  - **Product Definition & Architectural Foundation** (AI Product Manager): Guides product vision and requirements, generating a Product Requirements Document (PRD).
  - **UX Design & Feature Expansion** (AI UX Designer): Creates a user experience plan and a detailed UX Design Document.
  - **Technical Planning & Implementation Specifications** (AI Software Architect): Defines the technical implementation plan and produces a comprehensive Software Specification.
- **Conversational Interaction:** Engages users in dialogue until enough information is gathered, or the user requests document generation.
- **Document Generation & Storage:** Generates and stores documents (PRD, UX Design, Software Specification) at each stage. Documents are progressively improved as the workflow advances.
- **Verification Before Completion:** Ensures all required topics are covered before moving to the next phase.
- **Standalone or Integrated Usage:** Can be used as a standalone tool or integrated with Task Master for breaking down PRDs into development tasks.
- **Task Master Integration (Optional):** Allows further task management and breakdown of requirements into actionable tasks.
- **OpenRouter Model Selection:** Supports various AI models via the OpenRouter API.
- **Utility Scripts:** Includes scripts for testing and demonstrating Task Master integration.
- **Installation Options:** Supports global installation via npm and local development setup.
- **Test Suite:** Includes tests with results output for validation.
- **MIT Licensed.**

## Pricing
AI Expert Workflow MCP is open-source and free to use (MIT License). Any costs incurred would be from third-party services such as OpenRouter API usage.

## Source
[https://github.com/bacoco/ai-expert-workflow-mcp](https://github.com/bacoco/ai-expert-workflow-mcp)