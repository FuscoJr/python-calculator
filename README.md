# Python Calculator

An early Python learning project containing several versions of an interactive calculator.

The repository preserves the progression of the exercise in Python scripts and Jupyter notebooks. **V2 is the latest version.**

## Features in V2

- Addition, subtraction, multiplication and division.
- Decimal-number input.
- Retry prompts for invalid numbers and operators.
- A message when attempting division by zero.
- Continue calculating with the previous result or start a new calculation.

## Versions and files

The repository contains V0, V0.5, V1 and V2. Earlier versions are preserved as learning history and do not have all the behaviour described for V2.

```text
PY/                 # Python scripts
Notebook(GitHub)/   # Corresponding Jupyter notebooks
Screenshots/        # Example output
```

The V2 script and notebook contain the same calculation logic.

## Requirements

- Python 3.
- Jupyter Notebook only if using the notebook version.

The V2 Python script has no external dependencies.

## Run the latest script

From the repository root:

```sh
python PY/Calculator_V2.py
```

Enter a number, choose an operator (`+`, `-`, `*`, `/`), then enter the second number.

After a calculation:

| Choice | Action |
|---|---|
| C | Continue using the result |
| N | Start a new calculation |
| Q | Quit |

At number prompts, `Q`, `QUIT` and `EXIT` also quit the program.

## Open the latest notebook

Install Jupyter Notebook if needed:

```sh
python -m pip install notebook
```

From the repository root:

```sh
jupyter notebook "Notebook(GitHub)/Calculator_V2.ipynb"
```

Run the cells from top to bottom and respond to the interactive prompts.

## Learning focus

- Functions and return values.
- Conditional logic and loops.
- Handling invalid numeric input.
- Reusing results between calculations.
- Developing an exercise through successive versions.

## Current limitations

- Quit commands are not accepted at the operator prompt, despite the introductory message saying they work at any time.
- Earlier versions have less input validation than V2.
- The repository does not currently include automated tests.

Cleanup and remaining improvements are tracked in [issue #1](https://github.com/FuscoJr/python-calculator/issues/1).
