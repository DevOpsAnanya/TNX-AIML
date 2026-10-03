# Track B — Advanced Python: Week 1 Checklist

**Track B** is for members who are comfortable with variables, functions, and loops, and want to
gradually move toward Python libraries. This week covers classes, exceptions, comprehensions,
iterators, generators, packaging, and the beginning of numpy and matplotlib. Every day ends with a
small hands-on deliverable. Flip each `- [ ]` to `- [x]` as you finish, then commit your changes
in your own fork.

**Scope:** write Python like a toolmaker, not just a scriptrunner. You will end the week able to
organize code into classes and modules, handle errors, use comprehensions and generators, and run a
real numpy + matplotlib analysis.

---

## Sunday 4 Oct 2026 — Setup + foundations check

- [ ] **Install Python 3.12+ and verify** — confirm with `python --version`. Why it matters: libraries next week need a recent, consistent interpreter.
  - https://www.python.org/downloads/
- [ ] **Set up a simple project folder** — a folder with `src/`, a data folder, and a `README.md`, plus a `.gitignore` for `__pycache__` and `.env`. Why it matters: you will reuse this layout for every week.
  - https://docs.python.org/3/library/venv.html
- [ ] **Create a virtual environment and confirm it works** — `python -m venv .venv`, activate it, and check `pip --version`. Why it matters: every project needs an isolated place for packages.
  - https://docs.python.org/3/library/venv.html
  - https://pip.pypa.io/en/stable/getting-started/
- [ ] **Quick foundations check** — write a small script that uses a list, a loop, a conditional, and a function, and confirm it runs. Why it matters: it proves you have the base you need before we add new ideas.
  - **Deliverable:** your workspace folder with a working test script.

## Monday 5 Oct 2026 — Object-oriented programming

- [ ] **Classes and objects** — `__init__`, attributes, and methods. Why it matters: classes are how you bundle data and behavior into reusable tools.
  - https://docs.python.org/3/tutorial/classes.html
- [ ] **Methods vs functions, and `self`** — instance methods, the role of `self`, and calling methods on objects. Why it matters: the biggest source of early confusion in Python.
  - https://docs.python.org/3/tutorial/classes.html
- [ ] **Inheritance and `super()`** — subclassing, overriding, and calling the parent class. Why it matters: lets you extend existing tools without rewriting them.
  - https://docs.python.org/3/tutorial/classes.html
- [ ] **Mini project: a `Stock` and a `Portfolio` class** — model a share with a price and a portfolio that holds and values several shares. Why it matters: a realistic, small, object-oriented program.
  - **Deliverable:** `portfolio.py` that prints the total value.

## Tuesday 6 Oct 2026 — Exceptions and file I/O

- [ ] **Reading and writing files** — `open()`, `read`, `write`, and `with` for clean-up. Why it matters: file I/O is the first step from pure computation to real data.
  - https://docs.python.org/3/tutorial/inputoutput.html
  - https://docs.python.org/3/tutorial/errors.html
- [ ] **Reading CSV files** — parse a small CSV into a list of rows and print a summary. Why it matters: nearly every data task starts with a delimited text file.
  - https://docs.python.org/3/library/csv.html
- [ ] **Handling exceptions** — `try`, `except`, `else`, `finally`, and raising specific errors. Why it matters: bad input and missing files are guaranteed, not hypothetical.
  - https://docs.python.org/3/tutorial/errors.html
- [ ] **Robust file reader** — a function that reads a CSV, catches a missing file and a bad row, and reports them. Why it matters: turns the Wednesday deliverable into something that does not crash on bad data.
  - **Deliverable:** `reader.py` with output for a clean file and for a broken one.

## Wednesday 7 Oct 2026 — Comprehensions and lambdas

- [ ] **List comprehensions** — the compact form of mapping and filtering. Why it matters: the single most common Python idiom you will read and write.
  - https://docs.python.org/3/tutorial/datastructures.html
- [ ] **Dict and set comprehensions** — building dictionaries and sets inline. Why it matters: the same idea, applied to mappings and uniqueness.
  - https://docs.python.org/3/tutorial/datastructures.html
- [ ] **Lambdas and the `map` / `filter` built-ins** — small anonymous functions, and when to prefer a named function. Why it matters: they appear everywhere in libraries and notebooks.
  - https://docs.python.org/3/reference/expressions.html
- [ ] **Refactor Friday's work into comprehensions** — rewrite your list-building loops compactly, and time both to see the tradeoff. Why it matters: shows when brevity helps and when it hurts.
  - **Deliverable:** a small benchmark table in a notebook or script.

## Thursday 8 Oct 2026 — Iterators and generators

- [ ] **Iterables, iterators, and the `iter()`/`next()` protocol** — why they exist and what makes an object iterable. Why it matters: the foundation of `for` loops, and of lazy data processing.
  - https://docs.python.org/3/howto/functional.html
  - https://docs.python.org/3/library/stdtypes.html
- [ ] **Generator functions with `yield`** — producing values lazily, one at a time. Why it matters: lets you process large datasets without loading them all into memory.
  - https://docs.python.org/3/howto/functional.html
- [ ] **Generator expressions** — the one-line `(x for x in ...)` form. Why it matters: the memory-light sibling of a list comprehension.
  - https://docs.python.org/3/howto/functional.html
- [ ] **A streaming line reader** — a generator that yields lines from a file one at a time, and counts them without storing them. Why it matters: a concrete use you will repeat with big data.
  - **Deliverable:** `stream.py` and the count it prints for a sample file.

## Friday 9 Oct 2026 — Modules, venv, and pip

- [ ] **Writing and importing your own modules** — splitting code across files and using `import`. Why it matters: the day your scripts stop being one-file programs.
  - https://docs.python.org/3/tutorial/modules.html
- [ ] **Packages and `__init__.py`** — organizing modules into a package and importing it. Why it matters: prepares you for structured projects and libraries.
  - https://docs.python.org/3/tutorial/modules.html
- [ ] **Installed packages with venv and pip** — create a project-specific environment, install `numpy`, `pandas`, and `matplotlib`, and import them. Why it matters: this is exactly how the tools you will use for weeks 2 and 3 are set up.
  - https://docs.python.org/3/library/venv.html
  - https://pip.pypa.io/en/stable/
  - https://numpy.org/doc/stable/user/quickstart.html
- [ ] **A multi-file script** — refactor `portfolio.py` into `portfolio.py`, `models.py`, and a `__main__.py` entry point, and run it. Why it matters: moves you from script to package.
  - **Deliverable:** the project tree and a successful run.

## Saturday 10 Oct 2026 — NumPy basics

- [ ] **Arrays vs lists** — why numpy arrays are faster and memory-lighter for numbers. Why it matters: the entire data stack after this rests on arrays.
  - https://numpy.org/doc/stable/user/quickstart.html
- [ ] **Creating and inspecting arrays** — `np.array`, `shape`, `dtype`, `reshape`, and `arange`/`linspace`. Why it matters: reading and inspecting data is the first step of any analysis.
  - https://numpy.org/doc/stable/user/quickstart.html
  - https://numpy.org/doc/stable/user/basics.types.html
- [ ] **Universal functions and broadcasting** — element-wise math and how numpy aligns shapes. Why it matters: the core pattern behind nearly every numeric operation.
  - https://numpy.org/doc/stable/user/quickstart.html
- [ ] **Mini analysis** — load two small numeric files, compute row means and a correlation matrix, and print a summary. Why it matters: your first real numpy exercise with a deliverable.
  - **Deliverable:** `numpy_basics.py` with the printed summary.

## Sunday 11 Oct 2026 — pandas + matplotlib intro

- [ ] **Introducing pandas** — the `DataFrame` and `Series`, and why tabular data has a dedicated tool. Why it matters: pandas is the standard way to work with tables in Python.
  - https://pandas.pydata.org/docs/getting_started/index.html
- [ ] **Loading and inspecting a dataset** — `read_csv`, `head`, `info`, `describe`, and selecting columns and rows. Why it matters: every pandas session starts with inspection.
  - https://pandas.pydata.org/docs/getting_started/index.html
- [ ] **Plotting with matplotlib** — `plot`, `label`, `title`, and `show`. Why it matters: a picture is the fastest way to check what your data actually looks like.
  - https://matplotlib.org/stable/tutorials/pyplot.html
- [ ] **First pandas plot** — make a line chart of two columns and save it to a file. Why it matters: connects data, analysis, and visualization in one deliverable.
  - **Deliverable:** `pandas_viz.py` producing a saved PNG.

## Monday 12 Oct 2026 — Review, small library exercise, and worksheet

- [ ] **Review the week** — read back every day's deliverable and confirm each runs cleanly.
- [ ] **Catch up on anything missed**, using the official numpy and pandas manuals as references.
- [ ] **Small library exercise** — pick one thing from the week you find hardest (a generator, a class, a pandas grouping), and implement it from memory, then verify it with a tiny script.
- [ ] **Complete the Track B worksheet** — fill in every row and the reflection section for week 1.
  - [Track B worksheet](week-01/track-b/worksheet.md)
