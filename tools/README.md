# Tools

This directory contains tools that extend the capabilities of SIO Copilot agents and skills.

## What is a Tool?

A tool is an integration or utility that agents and skills can invoke at runtime. Tools typically wrap external APIs, CLI utilities, or internal services to provide a consistent interface for agents to call.

## Directory Structure

Each tool should live in its own subdirectory named after the tool:

```
tools/
└── <tool-name>/
    ├── README.md        # Description, inputs, outputs, and usage examples
    ├── tool.yml         # Tool definition / configuration
    └── ...              # Implementation files
```

## Contribution Guidelines

- Give your tool a clear, descriptive name (use lowercase with hyphens, e.g. `jira-search`).
- Include a `README.md` inside your tool's folder that explains:
  - What the tool does
  - Required configuration (API keys, endpoints, etc.)
  - Input / output contract
  - Example usage
- Handle errors gracefully and return meaningful error messages.
- Avoid bundling secrets in the repository; use environment variables or a secrets manager.
