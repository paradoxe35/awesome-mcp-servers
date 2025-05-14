# erikhoward/adls-mcp-server

**Source:** [GitHub Repository](https://github.com/erikhoward/adls-mcp-server)

**Category:** file-management-mcp-servers  
**Tags:** mcp, azure, cloud-storage, file-management, open-source

## Description
`erikhoward/adls-mcp-server` is an open-source Model Context Protocol (MCP) server implementation for Azure Data Lake Storage Gen2 (ADLS2). It provides a standardized interface for managing containers, files, and metadata in Azure Data Lake Storage through MCP tools.

## Features
- **Filesystem (Container) Operations:**
  - `list_filesystems`: List all filesystems in the storage account
  - `create_filesystem`: Create a new filesystem
  - `delete_filesystem`: Delete an existing filesystem
- **File Operations:**
  - `upload_file`: Upload a file to ADLS2
  - `download_file`: Download a file from ADLS2
  - `file_exists`: Check if a file exists
  - `rename_file`: Rename/move a file
  - `get_file_properties`: Get file properties
  - `get_file_metadata`: Get file metadata
  - `set_file_metadata`: Set file metadata
  - `set_file_metadata_json`: Set multiple metadata key-value pairs using JSON
- **Directory Operations:**
  - `create_directory`: Create a new directory
  - `delete_directory`: Delete a directory
  - `rename_directory`: Rename/move a directory
  - `directory_exists`: Check if a directory exists
  - `directory_get_paths`: Get all paths under the specified directory
- **Authentication:**
  - Supports authentication via Azure Storage Account Key or Azure CLI credentials
- **Configurable Environment Variables:**
  - `LOG_LEVEL`: Logging level (default: INFO)
  - `UPLOAD_ROOT`: Root directory for uploads (default: ./uploads)
  - `DOWNLOAD_ROOT`: Root directory for downloads (default: ./downloads)
  - `AZURE_STORAGE_ACCOUNT_NAME`: Azure ADLS2 storage account name (required)
  - `AZURE_STORAGE_ACCOUNT_KEY`: Azure ADLS2 storage account key (optional)
  - `READ_ONLY_MODE`: Option to run the server in read-only mode (default: true)
- **Integration:**
  - Can be configured for use with Claude Desktop
- **Development:**
  - Python 3.13+ required
  - Easy setup for local development and contribution
- **Open Source:**
  - Licensed under the MIT License

## Pricing
- **Open Source, Free to Use**
  - Licensed under MIT License

## License
MIT License