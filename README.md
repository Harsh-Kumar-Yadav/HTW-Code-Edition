# HTW Code Edition

Welcome to **HTW Code Edition** — a beginner-friendly bug-fixing challenge for first-year programmers.

Your task is to inspect each program, reproduce its incorrect behaviour, identify the bug, and submit a fix. The source files intentionally contain bugs. They are not examples of correct solutions.

## Challenge rules

1. Open the GitHub Issue linked below for your challenge.
2. Read the expected behaviour and reproduce the problem using the provided example.
3. Fix the program while keeping the intended behaviour and input/output format.
4. Test normal cases and edge cases.
5. Submit your fix according to the event organiser's instructions. Do not post solutions publicly while the event is running.

**Please do not publish solutions or spoilers in issue comments.** Ask for hints in the issue if needed.

## Challenges

### C

| Issue | File | Difficulty | Points |
|---|---|---|---:|
| [Issue #1 — Sum of Numbers](https://github.com/prathmyx/HTW-Code-Edition/issues/1) | [C/01-sum-of-numbers.c](C/01-sum-of-numbers.c) | Easy | 5 |
| [Issue #2 — Even or Odd](https://github.com/prathmyx/HTW-Code-Edition/issues/2) | [C/02-even-or-odd.c](C/02-even-or-odd.c) | Easy | 5 |
| [Issue #3 — Largest of Three](https://github.com/prathmyx/HTW-Code-Edition/issues/3) | [C/03-largest-of-three.c](C/03-largest-of-three.c) | Medium | 10 |
| [Issue #4 — Multiplication Table](https://github.com/prathmyx/HTW-Code-Edition/issues/4) | [C/04-multiplication-table.c](C/04-multiplication-table.c) | Easy | 5 |
| [Issue #5 — Count Positive Numbers](https://github.com/prathmyx/HTW-Code-Edition/issues/5) | [C/05-count-positive-numbers.c](C/05-count-positive-numbers.c) | Medium | 10 |
| [Issue #6 — Grade Calculator](https://github.com/prathmyx/HTW-Code-Edition/issues/6) | [C/06-grade-calculator.c](C/06-grade-calculator.c) | Medium | 10 |

### Python

| Issue | File | Difficulty | Points |
|---|---|---|---:|
| [Issue #7 — Number Guessing](https://github.com/prathmyx/HTW-Code-Edition/issues/7) | [Python/01-number-guessing.py](Python/01-number-guessing.py) | Medium | 10 |
| [Issue #8 — Simple Calculator](https://github.com/prathmyx/HTW-Code-Edition/issues/8) | [Python/02-simple-calculator.py](Python/02-simple-calculator.py) | Easy | 5 |
| [Issue #9 — Countdown Counter](https://github.com/prathmyx/HTW-Code-Edition/issues/9) | [Python/03-countdown-counter.py](Python/03-countdown-counter.py) | Easy | 5 |

## Running the programs

C programs can be compiled with GCC:

```bash
gcc C/01-sum-of-numbers.c -o challenge
./challenge
```

Run a Python program with Python 3:

```bash
python3 Python/01-number-guessing.py
```

Choose the matching file for the issue you are working on. Each issue contains a reproduction example and the expected behaviour, but not the solution.

## Labels and scoring

Each issue carries one difficulty label and one points label:

- `difficulty:easy` or `difficulty:medium`
- `points:5` or `points:10`

Have fun, test carefully, and happy debugging!
