# com5024-smart-home-automation

### Local Setup
1. Clone the repo
2. Run `uv venv` to create a virtual environment
3. Run `uv sync` to install dependencies

### Feature Setup
Setup individual features by creating a folder in the `src` directory. Any tests for the feature should be placed in a `tests` subfolder within the feature directory. See the `example_feature` for an example.

### Running tests
The command below will run all the tests across the project, and should be run from the repo root:
```shell
uv run pytest
```