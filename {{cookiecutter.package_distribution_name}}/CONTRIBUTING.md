# Contributing to {{ cookiecutter.package_distribution_name }}

## Set up for development

Activate a Python 3.11+ virtual environment, then run in the project folder:

    python -m pip install -e .

## Run the tests

    python -c "from {{ cookiecutter.package_import_name }} import greet; print(greet('Hee'))"

Expected output: `Hello, Hee!`

## Send a change

1. Create a branch from `main` and commit your change: `git switch -c my-change main`
2. Push the branch: `git push -u origin my-change`
3. Open a pull request from your branch into `main` on GitHub.
