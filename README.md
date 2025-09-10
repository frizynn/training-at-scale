# Training at Scale

A project for training models at scale using JAX.

## Features

- JAX-based machine learning workflows
- GPU acceleration support
- Modern Python packaging with pyproject.toml
- Comprehensive development tools

## Installation

### Basic Installation

```bash
# Install UV (if not already installed)
pip install uv

# Create virtual environment
uv venv .venv

# Activate virtual environment
source .venv/bin/activate  # On Windows: .venv\Scripts\activate

# Install dependencies
uv sync
```

### GPU Support

```bash
uv sync --extra gpu
```

### Development Setup

```bash
uv sync --extra dev
```

## Usage

```python
import jax
import jax.numpy as jnp

# Your JAX code here
x = jnp.array([1, 2, 3, 4])
print(f"JAX version: {jax.__version__}")
```

## Development

- **Code formatting**: `black .`
- **Import sorting**: `isort .`
- **Type checking**: `mypy .`
- **Testing**: `pytest`
- **Linting**: `flake8 .`

## License

MIT License
