# Track A — Python Basics: Week 1 Checklist

**Track A** is for members who know zero or minimal coding, or who want to brush up the basics.
Work through the checklist in order, one day at a time. Every day ends with a small hands-on
deliverable — reading alone is not the work. Flip each `- [ ]` to `- [x]` as you finish it, then
commit your changes in your own fork.

**Scope:** Python syntax and building blocks. The goal is to be able to write, run, and debug a small Python program by the end of the week.

---

## Sunday 4 Oct 2026 — Setup + your first program

- [ ] **Install Python 3.12+** — download from python.org and confirm with `python --version`. Why it matters: every topic this week runs on a real interpreter.
  - https://www.python.org/downloads/
- [ ] **Pick an editor: VS Code with the Python extension, or Google Colab.** Why it matters: you need a reliable place to type and run code every day.
  - VS Code: https://code.visualstudio.com/docs/languages/python
  - Kaggle Learn (free, browser-based): https://www.kaggle.com/learn/python
- [ ] **Run your first program** — print your name and a short greeting with `print()`. Why it matters: it confirms your setup works before we touch real logic.
  - **Deliverable:** a file `hello.py` that prints two lines; paste the output snippet.

## Monday 5 Oct 2026 — Syntax, print, input, variables, types

- [ ] **Comments and basic syntax** — reading and writing a clean script. Why it matters: readable code is the foundation of everything after this.
  - https://docs.python.org/3/tutorial/introduction.html
- [ ] **Variables and built-in types** — `int`, `float`, `str`, `bool`; assignment and naming. Why it matters: variables are how programs remember data between steps.
  - https://docs.python.org/3/library/stdtypes.html
- [ ] **Input and type conversion** — `input()`, and turning strings into numbers with `int()` / `float()`. Why it matters: programs that only print fixed text are not very useful.
  - https://docs.python.org/3/library/functions.html#input
- [ ] **Your first mini scripts** — a small program that asks for a name and prints a personalized greeting with a number spelled out. Why it matters: ties input to output and type conversion together.
  - **Deliverable:** `greeting.py` that asks for a name and age, then prints a one-line summary.

## Tuesday 6 Oct 2026 — Operators and strings

- [ ] **Arithmetic operators** — `+ - * / // % **` and operator precedence. Why it matters: almost every computation a program does is a sequence of these.
  - https://docs.python.org/3/tutorial/introduction.html
- [ ] **Comparison and logical operators** — `==, !=, <, >, <=, >=` combined with `and`, `or`, `not`. Why it matters: comparison is what turns raw data into decisions.
  - https://docs.python.org/3/reference/expressions.html
  - https://realpython.com/python-operators-expressions/
- [ ] **String basics** — quotes, concatenation, f-strings, and `len()` / `.lower()` / `.upper()`. Why it matters: text is the most common data form in beginner projects.
  - https://docs.python.org/3/tutorial/introduction.html
  - https://realpython.com/python-strings/
- [ ] **Mini string calculator** — take two numbers and an operator, then print a formatted result. Why it matters: exercises operator precedence plus clean string output.
  - **Deliverable:** `calc.py` with a formatted result line.

## Wednesday 7 Oct 2026 — Conditionals

- [ ] **if / elif / else** — the basic decision structure. Why it matters: branching is what turns a recipe into a program.
  - https://docs.python.org/3/tutorial/controlflow.html
- [ ] **Truthiness** — how Python treats values as true/false in conditions. Why it matters: avoiding `if x == True` and handling empty lists/strings correctly.
  - https://docs.python.org/3/tutorial/controlflow.html
- [ ] **Mini guess-the-number game** — use `random.randint` and a loop to compare a guess against a secret. Why it matters: combines conditionals, input, and math in one small, complete program.
  - **Deliverable:** `guess.py` that gives the user up to 5 guesses and prints a win/lose message.

## Thursday 8 Oct 2026 — Loops

- [ ] **for loops and range()** — iterating a fixed number of times. Why it matters: the workhorse of repeated computation.
  - https://docs.python.org/3/tutorial/controlflow.html
- [ ] **while loops and loop control** — `break` and `continue`. Why it matters: lets you write interactive or condition-driven repetition.
  - https://docs.python.org/3/tutorial/controlflow.html
- [ ] **Loop patterns** — counting, summing, and building lists. Why it matters: these patterns recur in every data task ahead.
  - https://docs.python.org/3/tutorial/controlflow.html
- [ ] **Number-guessing loop with a tally** — the guess game from Wednesday, now counting attempts and letting the user retry. Why it matters: extends the Wednesday deliverable into real control flow.
  - **Deliverable:** updated `guess.py` and its displayed session.

## Friday 9 Oct 2026 — Lists and dictionaries

- [ ] **Lists** — creation, indexing, slicing, and common methods. Why it matters: lists are the default ordered collection in Python.
  - https://docs.python.org/3/tutorial/datastructures.html
  - https://docs.python.org/3/library/stdtypes.html
- [ ] **List operations** — `append`, `extend`, `insert`, `remove`, `pop`, and sorting. Why it matters: they are the operations you will actually use on data.
  - https://docs.python.org/3/tutorial/datastructures.html
- [ ] **Dictionaries** — key/value pairs, lookup, and safe access. Why it matters: the primary way to map labels to values, and the closest thing Python has to a spreadsheet cell.
  - https://docs.python.org/3/tutorial/datastructures.html
  - https://realpython.com/python-dicts/
- [ ] **Student grades report** — load a small list of names and a parallel list (or dict) of scores, then print each student's letter grade. Why it matters: practices lists, dicts, loops, and conditionals in one deliverable.
  - **Deliverable:** `grades.py` and its printed report.

## Saturday 10 Oct 2026 — Functions

- [ ] **Defining and calling functions** — `def`, parameters, `return`, and docstrings. Why it matters: functions are how code becomes reusable and testable.
  - https://docs.python.org/3/tutorial/controlflow.html
- [ ] **Scope and defaults** — local vs global variables, and default arguments. Why it matters: protects your data and makes functions easier to call.
  - https://docs.python.org/3/tutorial/controlflow.html
- [ ] **Functions over collections** — `min`, `max`, `sum`, `len`, and list comprehensions. Why it matters: builds on Friday and prepares you for advanced Python.
  - https://docs.python.org/3/library/functions.html
- [ ] **A tool you can reuse** — a function that converts a list of numbers into a list of letter grades, plus a small demo. Why it matters: moves the Friday deliverable into a clean, reusable form.
  - **Deliverable:** `grades.py` with one reusable function and a short demo.

## Sunday 11 Oct 2026 — Combining fundamentals

- [ ] **Write and run a small program from scratch** — a single script that asks for a few inputs and uses variables, conditionals, loops, and functions to produce a result. Why it matters: integration is the skill that separates beginners from people who can actually build things.
  - https://docs.python.org/3/tutorial/introduction.html
- [ ] **Debugging basics** — reading tracebacks and using `print()` and `pdb` to find the fault. Why it matters: debugging is a daily skill, not a last resort.
  - https://docs.python.org/3/tutorial/errors.html
- [ ] **Mini project** — a "monthly bill estimator" or "tip calculator": inputs, types, conditionals, loops, and functions. Why it matters: applies the whole week in one deliverable.
  - **Deliverable:** `budget.py` with input, calculation, and a formatted output summary.

## Monday 12 Oct 2026 — Review, catch-up, and worksheet

- [ ] **Review the week** — read back every day's deliverable and confirm each one runs cleanly.
- [ ] **Catch up on anything missed**, using the official Python tutorial as your reference.
- [ ] **Complete the Track A worksheet** — fill in every row and the reflection section for week 1.
  - [Track A worksheet](week-01/track-a/worksheet.md)
