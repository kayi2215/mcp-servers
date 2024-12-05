# MCP Servers

A collection of Model Context Protocol (MCP) servers for enhanced session management and task automation.

## Servers

### 1. Enhanced Session Manager
- Advanced session management with checkpoints
- Indexing and search capabilities
- Change tracking and history

### 2. Task Management Server
- Project and task tracking
- Component management
- Progress monitoring

## Installation

```bash
npm install
```

## Usage

```bash
# Start Enhanced Session Manager
node servers/session-manager/index.js

# Start Task Management Server
node servers/task-manager/index.js
```

## Configuration

Create a `.env` file with:

```env
DB_PATH=./data/sessions.db
LOG_LEVEL=info
```

## Features

1. Session Management
   - Checkpoints and rollbacks
   - Session indexing
   - Change tracking
   - Search capabilities

2. Data Storage
   - SQLite integration
   - Efficient indexing
   - Data versioning

3. Task Automation
   - Project tracking
   - Component management
   - Progress monitoring

## Structure

```
mcp-servers/
├── servers/
│   ├── session-manager/
│   │   └── index.js
│   └── task-manager/
│       └── index.js
├── package.json
└── README.md
```

## License

MIT