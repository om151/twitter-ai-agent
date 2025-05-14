# MCP Twitter Post Project

This project demonstrates how to create a Twitter post using an MCP server and Google Gemini AI.

## Overview

- **Server**: Provides a tool to post a status update to Twitter using the MCP protocol.
- **Client**: Uses Google Gemini AI to interact with the MCP server and call the Twitter posting tool.

### How It Works

1. The server exposes a tool named `createPost` that posts a status update to Twitter.
2. The client connects to the server, uses Google Gemini AI to generate content, and calls the `createPost` tool to post the generated content to Twitter.