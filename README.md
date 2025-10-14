# Knowledge AI (Problem Set 2)

This project is a simple introduction to **knowledge representation and reasoning** using classic **Knights and Knaves** logic puzzles.

It was created as **Problem Set 2 (Knowledge)** for our **Introduction to Artificial Intelligence** course.

## Knights and Knaves?

In these puzzles:
- A **Knight** always tells the truth.
- A **Knave** always lies.
- Each character is exactly one of the two.

We write what each character says using logic, then let the program figure out who must be a knight or a knave.

## Files

| File | Purpose |
|------|---------|
| `logic.py` | Basic logic system (symbols, AND, OR, NOT, implication, and model checking). |
| `puzzles.py` | Defines the puzzles and prints the results. |

## How It Works

1. We create symbols like: `"A is a Knight"` and `"A is a Knave"`.
2. We enforce that exactly one of those is true for each person.
3. We translate each statement into logic.
4. The program tests all possibilities (models) and keeps only the ones that fit the rules.
5. Anything true in every valid model is printed.

## Running the Program

```bash
python puzzles.py
```

You will see output for each puzzle showing which roles are definitely true.

