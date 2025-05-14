# firebase-mcp

**Source:** [github.com/gannonh/firebase-mcp](https://github.com/gannonh/firebase-mcp)

An MCP (Model Context Protocol) server that enables LLM (Large Language Model) clients to interact programmatically with Firebase services, including Authentication, Firestore, and Storage. It exposes these services as MCP tools, allowing integration with LLM tools such as Claude Desktop, Cursor, Roo Code, and Cline.

## Features

### Authentication Tools
- **auth_get_user**: Retrieve user details by ID or email.

### Firestore Tools
- **firestore_add_document**: Add a document to a collection.
- **firestore_list_collections**: List available collections (optionally under a parent document, supports pagination).
- **firestore_list_documents**: List documents in a collection with optional filters and pagination.
- **firestore_get_document**: Retrieve a specific document by collection and ID.
- **firestore_update_document**: Update an existing document.
- **firestore_delete_document**: Delete a document by collection and ID.
- **firestore_query_collection_group**: Query across all sub-collections with the same name (supports filters, ordering, pagination, and limit).

### Storage Tools
- **storage_list_files**: List files in a storage directory (supports pagination).
- **storage_get_file_info**: Retrieve file metadata and download URL from storage.

### Other Notable Features
- Exposes Firebase services as MCP tools for LLM clients.
- Supports installation via npx or manual setup.
- Uses environment variables for Firebase service account and storage configuration.
- Supports testing using Firebase emulators and Vitest.
- Open source (MIT License).
- Written in TypeScript.

## Development
- Install dependencies with `npm install`.
- Build with `npm run build`.
- Test with `npm run test:emulator` after configuring Firebase emulators.
- Modular architecture with separate clients for Authentication, Firestore, and Storage.

## Pricing
- Open source and free to use (MIT License).

## Category
- cloud-devops-mcp-servers

## Tags
- mcp, firebase, cloud, authentication, storage