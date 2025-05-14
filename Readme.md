# MCP Twitter Post Project

This project demonstrates how to create a Twitter post using an MCP server and Google Gemini AI.

## Overview

- **Server**: Provides a tool to post a status update to Twitter using the MCP protocol.
- **Client**: Uses Google Gemini AI to interact with the MCP server and call the Twitter posting tool.

### How It Works

1. The server exposes a tool named `createPost` that posts a status update to Twitter.
2. The client connects to the server, uses Google Gemini AI to generate content, and calls the `createPost` tool to post the generated content to Twitter.

## Getting Started

### Prerequisites
- Node.js installed
- Twitter API credentials
- Google Gemini API key

### Installation
1. Clone the repository
```bash
git clone https://github.com/om151/twitter-ai-agent
cd twitter-ai-agent
```

2. Install dependencies
```bash
cd client
npm install
```
```bash
cd server
npm install
```


3. Configure environment variables
```bash
cp .env.example .env
# Edit .env with your API keys
```

### Running the Project
1. Start the MCP server
```bash
cd server
node index.js
```

2. Run the client
```bash
cd client
node index.js
```