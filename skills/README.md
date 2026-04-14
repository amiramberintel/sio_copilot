# Skills

This directory contains all reusable skills developed for the SIO team's Copilot agents.

## What is a Skill?

A skill is a discrete, reusable capability that can be invoked by one or more agents. Skills encapsulate specific actions — such as querying a data source, sending a notification, or processing a file — that agents can compose to accomplish larger tasks.

## Directory Structure

Each skill should live in its own subdirectory named after the skill:

```
skills/
└── <skill-name>/
    ├── README.md        # Description, inputs, outputs, and usage examples
    ├── skill.yml        # Skill definition / configuration
    └── ...              # Implementation files
```

## Contribution Guidelines

- Give your skill a clear, descriptive name (use lowercase with hyphens, e.g. `send-alert`).
- Include a `README.md` inside your skill's folder that explains:
  - What the skill does
  - Input parameters and expected output
  - Example usage
- Keep skills focused on a single responsibility.
- Avoid hard-coded values; use parameters for any configurable behavior.
