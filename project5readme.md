# Project 05: SortedStack

## Project Description
This Java program allows users to enter integers, which are pushed into a stack and sorted in ascending order. When the user types a non-integer, the input process ends and the sorted stack is printed. The program demonstrates stack manipulation using an auxiliary stack for sorting.

---

## How to Compile

```bash
javac SortedStack.java
```

---

## How to Run

```bash
java SortedStack
```

**Sample Input:**
```
9
2
6
done
```

**Sample Output:**
```
Sorted Stack (ascending order):
2
6
9
```

---

##  How to Generate Javadoc

```bash
javadoc -d docs SortedStack.java
```

This creates the Javadoc HTML files in the `docs/` directory.

---

##  Code Reuse & Design

- Uses `Stack<Integer>` from Java’s `java.util` package
- Applies a sorting algorithm using an auxiliary stack
- Handles exceptions and input gracefully
- Modular design with a single responsibility per method

---

## Files Included

- `SortedStack.java` — Java source file
- `SortedStack.class` — Compiled file
- `README.md` — This documentation file
- `docs/` — Generated JavaDoc files
