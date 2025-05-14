# bright8192/esxi-mcp-server

A VMware ESXi/vCenter management server based on the MCP (Model Control Protocol), providing REST API interfaces for virtual machine management.

- **Source:** [GitHub Repository](https://github.com/bright8192/esxi-mcp-server)
- **Category:** cloud-devops-mcp-servers
- **Tags:** mcp, cloud, vmware, infrastructure, open-source

## Features
- **Support for ESXi and vCenter Server connections**
- **RESTful API interface** with JSON-RPC support
- **Simple and secure authentication** using API keys
- **Real-time communication** via Server-Sent Events (SSE)
- **Complete virtual machine lifecycle management:**
    - Create VM
    - Clone VM
    - Delete VM
    - Power On/Off operations
    - List all VMs
- **Real-time performance monitoring:**
    - CPU usage
    - Memory usage
    - Storage usage
    - Network traffic statistics
- **SSL/TLS secure connection support**
- **Flexible configuration options:**
    - YAML, JSON, or environment variables
- **Configurable logging** (file path and log level)
- **Python 3.7+ compatible**

## Requirements
- Python 3.7+
- pyVmomi
- PyYAML
- uvicorn
- mcp-core

## Configuration
All configuration can be set via YAML file or environment variables. Key parameters include vCenter/ESXi host, user, password, datacenter, cluster, datastore, network, SSL options, API key, log file, and log level.

## Security Recommendations
- Use valid SSL certificates in production
- Enable API key authentication
- Set appropriate log levels
- Restrict API access scope

## License
MIT License

## Pricing
This project is open-source and free to use under the MIT License.