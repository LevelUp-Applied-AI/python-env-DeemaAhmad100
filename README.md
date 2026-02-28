[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/rZxQuJoV)
# AI.SPIRE Pre-Work — Python Toolchain

This repository is your workspace for Pre-Work Days 3–5.

| Day | PR | Topic |
|-----|-----|-------|
| 3 | PR-2 | Python venv Bootstrap + Sanity Script |
| 4 | PR-3 | Notebook vs Script: Same Output Two Ways |
| 5 | PR-4 | Compute & Debug Evidence Pack |

## Setup

Install Python 3.11 from [python.org](https://python.org), then:

```bash
python -m venv .venv
source .venv/bin/activate        # macOS / Linux
# source .venv/Scripts/activate  # Windows (Git Bash)
python -m pip install --upgrade pip
python -m pip install -r requirements-prework.txt
```

## Submitting PRs

1. Create a branch named for the PR task (e.g., `pr-02-python-env`)
2. Complete the work
3. Push the branch and open a PR from your branch to `main`
4. Submit the PR URL in TalentLMS

## When to use each 
i will choose the python script when the code be run by pytest or imported by another module 
In addition, I prefer to choose each one based on its specific use case:

I use Python scripts when I want the code to run automatically on a server or computer without needing to open an interface and click "run." I also use them for large-scale projects with many files, as scripts are faster and more efficient to execute.

On the other hand, I use Jupyter Notebooks when I want to experiment with code, test individual parts, and see the results immediately. Once I’m sure the code is working correctly, I transfer it to a .py file to make it official and ready to be used by anyone, including the Autograder.
