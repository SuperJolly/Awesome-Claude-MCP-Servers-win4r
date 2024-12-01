# Awesome Claude MCP Servers 🤖 [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of Model Context Protocol (MCP) servers optimized for Claude and other AI assistants.

## Contents
- [About MCP](#about-mcp)
- [Getting Started](#getting-started)
- [Core Servers](#core-servers)
- [Extended Capabilities](#extended-capabilities)
- [Development Tools](#development-tools)
- [Community Resources](#community-resources)

## About MCP

[Model Context Protocol (MCP)](https://modelcontextprotocol.io/) is an open protocol enabling AI models like Claude to securely interact with local and remote resources through standardized server implementations. These servers extend Claude's capabilities through file access, database connections, API integrations, and other contextual services.

## Getting Started

- 📚 [Model Context Protocol (MCP) Quickstart](https://glama.ai/blog/2024-11-25-model-context-protocol-quickstart)
- 💬 [Discord Community](https://discord.gg/TFE8FmjCdS)

## Legend

🏆 Official Implementation | 🐍 Python | 📱 TypeScript | 🏃 Go | ☁️ Cloud Service | 🏠 Local Service

## Core Servers

### File Systems 📂
- [@modelcontextprotocol/server-filesystem](https://github.com/modelcontextprotocol/servers/tree/main/src/filesystem) 📱 🏠
- [@modelcontextprotocol/server-google-drive](https://github.com/modelcontextprotocol/servers/tree/main/src/gdrive) 📱 ☁️
- [mark3labs/mcp-filesystem-server](https://github.com/mark3labs/mcp-filesystem-server) 🏃 🏠

### Search Engines 🔍
- [exa-labs/exa-mcp-server](https://github.com/exa-labs/exa-mcp-server) 🏆 📱 ☁️
- [@modelcontextprotocol/server-brave-search](https://github.com/modelcontextprotocol/servers/tree/main/src/brave-search) 📱 ☁️
- [ac3xx/mcp-servers-kagi](https://github.com/ac3xx/mcp-servers-kagi) 📱 ☁️
- [blazickjp/arxiv-mcp-server](https://github.com/blazickjp/arxiv-mcp-server) 🐍 ☁️

### Databases 🗄️
- [@modelcontextprotocol/server-postgres](https://github.com/modelcontextprotocol/servers/tree/main/src/postgres) 📱 🏠
- [@modelcontextprotocol/server-sqlite](https://github.com/modelcontextprotocol/servers/tree/main/src/sqlite) 🐍 🏠

## Extended Capabilities

### Knowledge & Memory 🧠
- [@modelcontextprotocol/server-memory](https://github.com/modelcontextprotocol/servers/tree/main/src/memory) 📱 🏠

### Version Control 📊
- [@modelcontextprotocol/server-github](https://github.com/modelcontextprotocol/servers/tree/main/src/github) 📱 ☁️
- [@modelcontextprotocol/server-gitlab](https://github.com/modelcontextprotocol/servers/tree/main/src/gitlab) 📱 ☁️
- [@modelcontextprotocol/server-git](https://github.com/modelcontextprotocol/servers/tree/main/src/git) 🐍 🏠

### Cloud Integration ☁️
- [Cloudflare MCP Server](https://github.com/cloudflare/mcp-server-cloudflare) 🏆 📱 ☁️

### Communication 💬
- [@modelcontextprotocol/server-slack](https://github.com/modelcontextprotocol/servers/tree/main/src/slack) 📱 ☁️

### Browser Automation 🌐
- [@modelcontextprotocol/server-puppeteer](https://github.com/modelcontextprotocol/servers/tree/main/src/puppeteer) 📱 🏠
- [@modelcontextprotocol/server-youtube](https://github.com/kimtaeyoon83/mcp-server-youtube-transcript) 📱 ☁️

### Location Services 🗺️
- [@modelcontextprotocol/server-google-maps](https://github.com/modelcontextprotocol/servers/tree/main/src/google-maps) 📱 ☁️

### Monitoring 📈
- [@modelcontextprotocol/server-sentry](https://github.com/modelcontextprotocol/servers/tree/main/src/sentry) 🐍 ☁️
- [@modelcontextprotocol/server-raygun](https://github.com/MindscapeHQ/mcp-server-raygun) 📱 ☁️

## Development Tools

### Frameworks 🛠️
- [Genkit MCP](https://github.com/firebase/genkit/tree/main/js/plugins/mcp) 📱
- [@modelcontextprotocol/server-langchain](https://github.com/rectalogic/langchain-mcp) 🐍
- [mark3labs/mcp-go](https://github.com/mark3labs/mcp-go) 🏃

### Integration Tools 🔧
- [pierrebrunelle/mcp-server-openai](https://github.com/pierrebrunelle/mcp-server-openai) 🐍 ☁️
- [@modelcontextprotocol/server-everything](https://github.com/modelcontextprotocol/servers/tree/main/src/everything) 📱 🏠
- [calclavia/mcp-obsidian](https://github.com/calclavia/mcp-obsidian) 📱 🏠
- [rusiaaman/wcgw](https://github.com/rusiaaman/wcgw/blob/main/src/wcgw/client/mcp_server/Readme.md) 🐍 🏠

## Community Resources

Want to ask Claude about Model Context Protocol? Add this file to your project:
[Claude MCP Instructions](https://modelcontextprotocol.io/llms-full.txt)
