# SIO Copilot

A central repository to collect all **agents**, **skills**, **scripts**, and **tools** for the SIO team.

## Repository Structure

```
sio_copilot/
├── agents/     # Autonomous AI agents built for SIO workflows
├── skills/     # Reusable capabilities invoked by agents
├── scripts/    # Utility and automation scripts
└── tools/      # Integrations and utilities used by agents and skills
```

| Directory | Purpose |
|-----------|---------|
| [`agents/`](./agents/) | Autonomous or semi-autonomous components that perform specific tasks |
| [`skills/`](./skills/) | Discrete, reusable capabilities that agents can compose |
| [`scripts/`](./scripts/) | Standalone automation and operational scripts |
| [`tools/`](./tools/) | Runtime integrations wrapping APIs, CLIs, or internal services |

## Getting Started

1. Browse the relevant directory for existing agents, skills, scripts, or tools.
2. Each item lives in its own subdirectory and includes a `README.md` with usage instructions.
3. To contribute a new item, create a subdirectory under the appropriate category and follow the guidelines in that category's `README.md`.

## Contribution Guidelines

- Follow the conventions described in each directory's `README.md`.
- Keep contributions focused and well-documented.
- Do not commit secrets, credentials, or sensitive data. Use environment variables or a secrets manager.
- Open a pull request with a clear description of what you are adding or changing.
