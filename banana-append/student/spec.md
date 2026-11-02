# Correctness spec: Banana Append

Your code is graded by running it against test cases. This file states exactly what those tests expect.
The assignment itself is in `instructions.md`.

| | |
|---|---|
| Language | Python 3 |
| The file you edit | `starting.py` |
| How it is run | the tests type input into your program and read what it prints |
| Visible tests | 2, in `tests-visible.py` |
| Hidden tests | 4, held back |
| Points for correctness | 100 |

## How a test passes

The tests type the input in, line by line, and then check what your program printed.
Your output must **end with** the expected text, so you can word your prompts however you like,
but the final answer must be formatted exactly as the examples show.

## The visible tests

| Test | Input | Expected |
|---|---|---|
| Success: simple phrase | `I like` | `I like Bananas!` |
| Success: single word | `Go` | `Go Bananas!` |

The hidden tests check the same rules on other values, including edge cases, so write code that works in general rather than code that matches the table.
