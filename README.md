# Python Workflow with Black, Ruff, GitHub Actions, and Pre-Commit Hooks

This project provides a Python development workflow that uses Black for code formatting,
Ruff for linting, GitHub Actions for continuous integration, and Pre-Commit Hooks for local testing.

## Installation
To use this workflow, you must have Python and Git installed on your system.
You use this as a template, or you can then clone this repository and install the necessary dependencies by running

```bash
git clone https://github.com/jheavejimenez/python-template.git
cd your_project
pip install -r requirements.txt
```

## Pre-Commit Hooks
This project uses Pre-Commit Hooks for local testing. To install the hooks, run the following command:
```bash
pre-commit install
```

The hooks will then run automatically before every commit. If any of the hooks fail, the commit will be aborted.

## Continuous Integration
This project uses GitHub Actions for continuous integration.
The workflow is defined in `.github/workflows/main.yml.`
The workflow will run on every push to the repository,
and it will run the black and ruff commands to ensure that the code is properly formatted and linted.
