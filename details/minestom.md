# Minestom

[Minestom](https://github.com/Minestom/Minestom) is an open-source, developer-centric Minecraft server library written in Java. It is designed to enable developers to create custom, high-performance Minecraft server software that does not include any vanilla features by default, providing a modular and extensible API.

## Features
- **Open-source Java library**: Minestom is a pure Java library and is available under the Apache-2.0 license.
- **No Mojang code**: Completely independent from Mojang's server code.
- **No vanilla features by default**: Provides a blank slate for custom server development.
- **Modern, modular API**: Designed for extensibility and ease of use for developers.
- **Multi-threaded architecture**: Utilizes a thread pool to manage chunks and instances for better performance and scalability.
- **Instance system**: Lightweight, scalable collections of blocks and entities (alternative to traditional worlds), supporting custom serialization and in-memory storage.
- **Blocks**: Visual representation of all blocks by default; custom handlers are required for interactive or special blocks.
- **Entities**: Flexible entity system without predefined passive/aggressive behavior; allows custom entity behaviors.
- **Inventory management**: Native support for inventories as client-server interfaces with clickable items and callbacks.
- **Command API**: Integrated with Brigadier for advanced command parsing and argument types.
- **High performance**: Designed to remove the overhead caused by unnecessary vanilla features, suitable for minigames, creative servers, and custom game modes.
- **Not compatible with Bukkit/Forge/Sponge plugins**: Does not implement their APIs.
- **Does not work with older clients**: Only supports newer Minecraft versions.
- **Extensive documentation and community support**: Includes official wiki, javadocs, and active GitHub repository.

## Pricing
- **Free and open-source** under the Apache-2.0 license.

## Links
- [GitHub Repository](https://github.com/Minestom/Minestom)
- [Official Website](https://minestom.net/)