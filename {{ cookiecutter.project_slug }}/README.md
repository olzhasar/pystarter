# {{ cookiecutter.project_slug }}

## Development

### Prerequisites

- [Python 3.11](https://www.python.org/downloads/)
- [Poetry](https://python-poetry.org/docs/#installation)

### Setup

Install the project dependencies using Poetry:

```bash
poetry install
```

Activate the virtual environment:

```bash
poetry shell
```

Setup the pre-commit hooks:

```bash
pre-commit install
```

### Testing

Run the test suite:

```bash
pytest
```

Start the test watcher:

```bash
ptw .
```
