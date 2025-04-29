# Weather MCP Tool

A command-line tool built with the Model Context Protocol (MCP) SDK for accessing weather information.

## Features

- Provides weather data via MCP
- Includes ESLint and Prettier configuration
- Uses Husky for pre-commit hooks
- Configured for VS Code with auto-formatting

## Installation

```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/weather-mcp.git
cd weather-mcp

# Install dependencies
yarn

# Build the project
yarn build

# Link the binary (optional)
yarn link
```

## Usage

After installation, you can use the tool:

```bash
weather --help
```

## Development

```bash
# Run linting
yarn lint

# Run formatting
yarn format

# Fix linting issues
yarn lint:fix
```

## Configuration

The tool uses MCP configuration to connect with models.

## License

MIT
