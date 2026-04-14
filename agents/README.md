# Agents

This directory contains all Copilot agents developed for the SIO team.

## What is an Agent?

An agent is an autonomous or semi-autonomous AI-powered component that can perform a specific task or set of tasks. Agents may interact with tools, APIs, and other agents to accomplish goals.

## Directory Structure

Each agent should live in its own subdirectory named after the agent:

```
agents/
└── <agent-name>/
    ├── README.md        # Description, usage, and configuration
    ├── agent.yml        # Agent definition / configuration
    └── ...              # Additional agent files
```

## Contribution Guidelines

- Give your agent a clear, descriptive name.
- Include a `README.md` inside your agent's folder that explains:
  - What the agent does
  - How to configure and run it
  - Any dependencies or prerequisites
- Document any required environment variables or secrets.
