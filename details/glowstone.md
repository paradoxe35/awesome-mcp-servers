# Glowstone

[Glowstone](https://github.com/GlowstoneMC/Glowstone) is a lightweight, high-performance open source Minecraft server for Java Edition, written from scratch in Java. It is designed to be fast, customizable, and compatible with plugins from the Bukkit, Spigot, and PaperMC ecosystems.

## Features
- **Open Source**: Entirely original codebase, not relying on decompiled Minecraft sources
- **Plugin Support**: Native support for plugins targeting the Bukkit, Spigot, and Paper APIs
- **High Performance**: Lightweight and efficient, with a thread-per-world model and minimal synchronization for speed
- **Customizability**: Easily configurable via a YAML configuration system (`glowstone.yml`), replacing standard server property files
- **Easy Contribution**: Lower barrier for contributors since it does not interface with proprietary or decompiled code
- **Self-contained Build**: Dependencies are shaded into the output jar for simple deployment
- **Colored Console Output**: Uses JLine for enhanced console experience, which can be disabled
- **Configurable Logging and Data**: Configuration and logs are neatly separated into their own subdirectories
- **MIT Licensed**: Released under the permissive MIT license
- **Compatible with Major Plugin APIs**: While not all plugins are guaranteed to work, the goal is to support all plugins that do not depend on Minecraft's internal server code
- **Original Implementation**: Does not require vanilla Minecraft server software to run
- **Active Community**: Ongoing development with contributions from 100+ developers

## Limitations
- Not all plugins are guaranteed to work, especially those relying on internal Minecraft or CraftBukkit code
- The project is not fully feature-complete and may lack some vanilla server features
- Less rigorous testing compared to the official Bukkit project

## Getting Started
- Requires Java (Oracle JDK or OpenJDK) and Maven for building from source
- Can be run directly with `java -jar glowstone.jar`
- Configuration is handled via `config/glowstone.yml`

## Category
- Game Server MCP Implementations

## Tags
- open-source, minecraft, java, plugin-support

## Pricing
Glowstone is free and open source software, released under the MIT license.