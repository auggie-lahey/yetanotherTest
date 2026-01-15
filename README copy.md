# testingbudabitclubgit

A simple Python "Hello World" project with GitHub Actions automation.

## Project Structure

- `src/main.py`: A simple Python script that prints a greeting message
- `.github/workflows/python-run.yml`: GitHub Actions workflow that runs the Python script on any push to any branch

## Running the Project

To run this Python script locally:

```bash
python src/main.py
```

## GitHub Actions

This project includes a GitHub Actions workflow that:

1. Triggers on any push or pull request to any branch
2. Sets up a Python 3.10 environment
3. Runs the Python script to verify it works correctly

The workflow configuration can be found in `.github/workflows/python-run.yml`.