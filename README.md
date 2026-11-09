# Optanovarchitect

Local architecture and planning toolkit for the OPTANOVA Worker system.

## Purpose

Optanovarchitect is a local-first project for describing, validating, and
rendering architecture artifacts used by OPTANOVA Worker workflows
(prompt systems, storefront pages, blog publishing, and CJ Dropshipping
automation). It runs entirely offline and stores everything on disk.

## Setup

Prerequisites: Python 3.12+ and [uv](https://github.com/astral-sh/uv).

```bash
# From the optanovarchitect directory
uv sync --dev

# Activate the environment
. .venv/bin/activate

# Run the CLI (placeholder entry point)
python -m optanovarchitect --help
```

## Stack

- Python 3.12+
- Packaging: uv / `pyproject.toml`

No git repository or remote is configured for this project yet.
