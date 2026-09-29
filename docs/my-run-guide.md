# Running the library demo

## Prerequisites

- Git 2.23 or later to clone the repository.
- JDK 17 or later, with both `java` and `javac` available on PATH.
- Python 3.9 or later.
- A terminal opened in the repository root, where `run.py` is located.

No Maven, Gradle, or third-party libraries are required.

## Run

```sh
python3 run.py demo
```

On Windows with the Python launcher, use the equivalent command:

```powershell
py -3 run.py demo
```

The runner compiles the Java application in a temporary directory and runs a
small library demonstration. It displays student and faculty borrowing limits,
searches for `git`, borrows a book for Alex, and prints a receipt and due date.
It then returns the book and displays the return fee and remaining active loans.
The demo uses the fixed date September 1, 2026, so its output is reproducible.
