## website-downloader

- **Category:** File Management MCP Servers
- **Source:** [https://github.com/pskill9/website-downloader](https://github.com/pskill9/website-downloader)
- **Tags:** mcp, web, file-management, automation

### Description
website-downloader is an MCP server that enables automated downloading of entire websites using `wget`. It preserves the original website structure and converts links for local use, making it suitable for web archiving and offline browsing.

### Features
- Downloads entire websites recursively using `wget`.
- Preserves the website's directory structure.
- Converts website links to work locally.
- Adds appropriate file extensions during download.
- Restricts downloads to the same domain to avoid external content.
- Includes all page requisites (e.g., CSS, images, scripts).
- Allows specifying maximum depth for recursive downloading (e.g., only the specified page, direct links, or deeper levels).
- Output directory for downloads can be customized.
- Runs as a specialized MCP server for automation in larger workflows.

### Usage
- Requires `wget` to be installed on the system.
- Main tool: `download_website` with the following parameters:
  - `url` (required): The website URL to download.
  - `outputPath` (optional): Directory for downloaded site (defaults to current directory).
  - `depth` (optional): Maximum recursion depth (defaults to infinite).

### Installation
- Install dependencies: `npm install`
- Build the server: `npm run build`
- Add to MCP settings as a server process.

### Pricing
- Open source (no pricing or commercial plans listed).
