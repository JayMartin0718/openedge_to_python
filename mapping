# OpenEdge to Python Mapping

## Control Flow Statements
| OpenEdge | Python | Description | Example |
|----------|--------|-------------|---------|
| DO WHILE | while | Executes a loop while a condition is true | `while x < 10: print(x); x += 1` |
| DO FOR | with | Context manager for resource handling | `with open("file.txt") as f: data = f.read()` |
| IF THEN ELSE | if...elif...else | Conditional statement | `if x > 10: print("High") elif x == 10: print("Equal") else: print("Low")` |
| LEAVE | break | Exits a loop prematurely | `for x in range(10): if x == 5: break` |
| NEXT | continue | Skips the current iteration and moves to the next loop iteration | `for x in range(5): if x == 2: continue; print(x)` |
| RETURN | return | Exits a function and optionally returns a value | `def add(a, b): return a + b` |
| RUN | function_call() | Calls a procedure or function | `def greet(): print("Hello"); greet()` |
| REPEAT | while True | Infinite loop until explicitly exited | `while True: print("Running")` |
| CASE | match...case | Matches values against patterns (Python 3.10+) | `match x: case 1: print("One") case 2: print("Two")` |
| ELSEIF | elif | Alternative condition in an if statement | `if x > 10: print("High") elif x == 5: print("Medium")` |
| END | pass | Marks the end of a block (optional in Python) | `def func(): pass` |

## Exception Handling
| OpenEdge | Python | Description | Example |
|----------|--------|-------------|---------|
| CATCH | except | Handles an exception | `try: x = 1 / 0 except ZeroDivisionError: print("Cannot divide by zero")` |
| FINALLY | finally | Executes cleanup code after try-except | `try: x = open("file.txt") finally: x.close()` |
| RAISE | raise | Manually raises an exception | `raise ValueError("Invalid input")` |

## Variable and Data Handling
| OpenEdge | Python | Description | Example |
|----------|--------|-------------|---------|
| DEFINE VARIABLE | variable_name = value | Declares and initializes a variable | `x = 10` |
| ASSIGN | = | Assigns a value to a variable | `x = "Hello"` |
| MESSAGE | print | Displays output to the user | `print("Hello, World!")` |
| UPDATE | input() | Prompts user for input and updates a value | `x = input("Enter name: ")` |
| EXPORT | json.dump | Writes structured data to a file | `import json; json.dump(data, open("file.json", "w"))` |
| IMPORT | json.load | Reads structured data from a file | `import json; data = json.load(open("file.json"))` |
