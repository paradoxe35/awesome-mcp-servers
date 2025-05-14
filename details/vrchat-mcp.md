# vrchat-mcp

**Category:** Messaging MCP Servers  
**Tags:** mcp, vrchat, messaging, api-integration  
**Source:** [GitHub Repository](https://github.com/sawa-zen/vrchat-mcp)

## Overview

`vrchat-mcp` is a Model Context Protocol (MCP) server designed for interacting with the VRChat API. It offers a standardized protocol to access a wide range of VRChat API endpoints, enabling structured retrieval and manipulation of user, friend, avatar, world, group, and notification data from VRChat.

## Features

- **User Related:**
  - Retrieve friends list (`vrchat_get_friends_list`)
  - Send friend requests (`vrchat_send_friend_request`)
- **Avatar Related:**
  - Search for avatars (`vrchat_search_avatars`)
  - Select and switch to a specific avatar (`vrchat_select_avatar`)
- **World Related:**
  - Search for worlds (`vrchat_search_worlds`)
  - Get list of favorited worlds (`vrchat_list_favorited_worlds`)
- **Instance Related:**
  - Create a new instance (`vrchat_create_instance`)
  - Get information about a specific instance (`vrchat_get_instance`)
- **Group Related:**
  - Search for groups (`vrchat_search_groups`)
  - Join a group (`vrchat_join_group`)
- **Favorites Related:**
  - Get a list of favorites (`vrchat_list_favorites`)
  - Add a new favorite (`vrchat_add_favorite`)
  - Get a list of favorite groups (`vrchat_list_favorite_groups`)
- **Invite Related:**
  - Get a list of invite messages (`vrchat_list_invite_messages`)
  - Request an invite (`vrchat_request_invite`)
  - Get a specific invite message (`vrchat_get_invite_message`)
- **Notification Related:**
  - Get a list of notifications (`vrchat_get_notifications`)
- **Authentication:**
  - Supports login and authentication with VRChat credentials and token
- **Integration:**
  - Can be used standalone or integrated with applications like Claude Desktop via configuration
- **Debugging Support:**
  - Works with MCP Inspector for debugging
- **Open Source:**
  - Licensed under the MIT License
- **Development:**
  - Written in TypeScript/JavaScript

## Pricing

This project is open source and free to use under the MIT License.

## License

MIT License
