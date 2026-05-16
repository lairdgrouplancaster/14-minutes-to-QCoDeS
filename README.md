# 14 minutes to QCoDeS

This repository contains a short VS Code notebook tutorial for getting started with QCoDeS using software-only dummy instruments.

The tutorial intentionally installs the latest available versions of QCoDeS and related packages, except where a package is installed from a named release tag. This keeps new users close to the current QCoDeS ecosystem. If a future package release changes behaviour, the notebook examples may need minor updates.

## Contents

- `14_minutes_to_QCoDeS.ipynb`: the tutorial notebook.

## Last tested with

- Python 3.11.9, as recorded in the notebook metadata.
- QCoDeS-Plotter v1.3.1.

The notebook includes a verification cell that prints the Python executable and the installed QCoDeS version for the environment actually being used.

## Generated files

Running the notebook creates local files such as the `.venv` environment, notebook checkpoints, logs, and the demo QCoDeS database. These are ignored by git.
