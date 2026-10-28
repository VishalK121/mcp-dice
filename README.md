# Dice MCP Server

A simple remote Model Context Protocol server built with
Next.js, TypeScript, and mcp-handler.

## Features

- Roll an N-sided die
- Input validation
- Streamable HTTP MCP endpoint

## Local development

Install dependencies:

npm install

Start the development server:

npm run dev

MCP endpoint:

http://localhost:3000/api/mcp

## Deployment

Import this repository into Vercel and deploy.

After deployment, connect your MCP client to:

https://YOUR-PROJECT.vercel.app/api/mcp
