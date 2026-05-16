# Contributing

## Cloning the repository in VS Code

1. Open VS Code.
2. Open the Command Palette with `Ctrl+Shift+P`.
3. Run `Git: Clone`.
4. Paste the GitHub repository URL.
5. Choose where to save the local copy.
6. When VS Code asks whether to open the cloned repository, choose `Open`.
7. If prompted, agree to trust the folder.

## Editing the notebook

1. Open this folder in VS Code.
2. Open `14_minutes_to_QCoDeS.ipynb`.
3. Select the `.venv` kernel, or create a fresh virtual environment by following the setup instructions in the notebook.
4. Make your edits in small, focused changes.
5. Restart the kernel and run the edited section, plus any setup cells it depends on.
6. Before committing, clear large or accidental outputs if they are not useful for the tutorial.

The tutorial intentionally installs the latest available versions of QCoDeS and related packages, except where a package is installed from a named release tag. Do not add pinned dependency files unless the tutorial policy changes.

## Check local files

Running the notebook may create local files such as `.venv`, `.ipynb_checkpoints`, logs, and `Demo_db.db`. These should stay untracked.

Check the working tree with:

```bash
git status --short
```

You should normally commit only:

- `14_minutes_to_QCoDeS.ipynb`
- `README.md`
- `.gitignore`
- `CONTRIBUTING.md`

## Commit and push

Stage the files you changed:

```bash
git add 14_minutes_to_QCoDeS.ipynb README.md .gitignore CONTRIBUTING.md
```

Commit with a short descriptive message:

```bash
git commit -m "Update tutorial instructions"
```

Push to GitHub:

```bash
git push
```

After pushing, check the repository page on GitHub to make sure the notebook renders as expected.
