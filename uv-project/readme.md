# Project with Virtual Environment set up with uv

## Requirements

- Python 3.11
- uv 0.1.0

## Installation

```bash
uv sync
```

## Activation/Deactivation (Optional)

```bash
source .venv/bin/activate
deactivate
```

## Install dependencies

```bash
uv add <package_name>
```

## Usage
The activation/deactivation is optional. 
You can run the virtual environment's python interpreter directly using `uv run`

```bash
uv run python
```