# Excalidraw MCP Server

This is a Model Context Protocol (MCP) server for Excalidraw, providing API functionality for operating on Excalidraw drawings.

<a href="https://glama.ai/mcp/servers/@i-tozer/excalidraw-mcp">
  <img width="380" height="200" src="https://glama.ai/mcp/servers/@i-tozer/excalidraw-mcp/badge" alt="Excalidraw Server MCP server" />
</a>

## Features

- Create, read, update, and delete Excalidraw drawings
- Export drawings to SVG, PNG, and JSON formats
- Simple file-based storage system

## Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/excalidraw-mcp.git
cd excalidraw-mcp

# Install dependencies
npm install

# Build the project
npm run build
```

## Usage

### Starting the Server

```bash
npm start
```

### API Endpoints

The server provides the following tools:

#### Drawing Management

- `create_drawing`: Create a new Excalidraw drawing
- `get_drawing`: Get an Excalidraw drawing by ID
- `update_drawing`: Update an Excalidraw drawing by ID
- `delete_drawing`: Delete an Excalidraw drawing by ID
- `list_drawings`: List all Excalidraw drawings

#### Export Operations

- `export_to_svg`: Export an Excalidraw drawing to SVG
- `export_to_png`: Export an Excalidraw drawing to PNG
- `export_to_json`: Export an Excalidraw drawing to JSON

## Development

### Project Structure

```
excalidraw-mcp/
├── src/
│   ├── common/
│   │   └── errors.ts
│   └── operations/
│       ├── drawings.ts
│       └── export.ts
├── index.ts
├── package.json
├── tsconfig.json
└── README.md
```

### Building

```bash
npm run build
```

### Running in Development Mode

```bash
npm run dev
```

## License

MIT