# Scripts

This directory contains utility and automation scripts used by the SIO team.

## What belongs here?

- One-off or recurring automation scripts (e.g. data migrations, report generation)
- Setup and bootstrap scripts for local development or CI/CD pipelines
- Operational runbooks implemented as executable scripts

## Directory Structure

Group related scripts in subdirectories when appropriate:

```
scripts/
├── setup/          # Environment setup and installation scripts
├── maintenance/    # Operational and maintenance scripts
└── <script.sh>     # Standalone scripts at the top level
```

## Contribution Guidelines

- Use a descriptive filename that conveys what the script does (e.g. `generate-report.sh`, `cleanup-old-logs.py`).
- Add a comment block at the top of every script with:
  - A brief description of what it does
  - Required environment variables or arguments
  - Example invocation
- Make shell scripts executable (`chmod +x <script>.sh`) and include a shebang line (e.g. `#!/usr/bin/env bash`).
- Prefer Python for complex logic; use Bash for simple shell automation.
