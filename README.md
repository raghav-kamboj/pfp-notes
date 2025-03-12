# pfp-notes
# Python Notes

## 1. Language Features
- **Interpreted Language**: Python executes code line by line without compilation.
- **High-Level and Easy to Learn**: The syntax is user-friendly and close to English.
- **Dynamically Typed**: No need to declare variable types explicitly.
- **Object-Oriented and Procedural Support**: Supports both paradigms.
- **Extensive Standard Library**: Includes modules for various functionalities.
- **Cross-Platform Compatibility**: Works on Windows, macOS, and Linux.
- **Automatic Memory Management**: Uses garbage collection.

## 2. Advantages
- **Easy Syntax and Readability**: Simple to understand.
- **Large Community Support**: Active developers and forums.
- **Rich Ecosystem and Libraries**: NumPy, Pandas, TensorFlow, etc.
- **Highly Scalable and Versatile**: Used in multiple domains.
- **Good for Prototyping and Rapid Development**: Quick application building.

## 3. Disadvantages
- **Slower Execution Speed** (Compared to C/C++).
- **High Memory Usage**.
- **Global Interpreter Lock (GIL)** Limits Multi-threading.
- **Not Ideal for Mobile Development**.

## 4. Python Applications
- **Web Development**: Django, Flask.
- **Data Science and Machine Learning**: Pandas, NumPy, TensorFlow.
- **Automation and Scripting**: Automating repetitive tasks.
- **Game Development**: Pygame.
- **Embedded Systems**.
- **Cybersecurity**.

## 5. Types of Errors
- **Syntax Errors**: Errors in Python syntax.
  ```python
  print("Hello" # Missing closing parenthesis
  ```
- **Runtime Errors**: Errors occurring during execution.
  ```python
  print(10 / 0)  # ZeroDivisionError
  ```
- **Logical Errors**: Errors that don’t crash the program but produce incorrect results.
  ```python
  # Incorrect average calculation
  total = 100
  count = 0
  avg = total / count  # Logical error: division by zero
  ```

## 6. Comments
- **Single-line Comment**: `# This is a comment`
- **Multi-line Comment**:
  ```python
  """
  This is a multi-line comment
  """
  ```

## 7. Identifiers and Keywords
- **Identifiers**: Names for variables, functions, classes.
- **Keywords**: Reserved words in Python (`if`, `else`, `while`, `import`, etc.).

## 8. Variables and Assignment
- Variables store data values.
- Assignment uses `=` operator.
  ```python
  x = 10
  name = "Python"
  ```

## 9. Expressions and Statements
- **Expression**: Produces a value (`x + y`, `a * b`).
- **Statement**: Executes an action (`print("Hello")`, `x = 5`).

## 10. Indentation
- Python uses indentation for code blocks.
  ```python
  if True:
      print("Indented block")
  ```

## 11. Data Types
### Numeric Types
- **Integer (`int`)**: Whole numbers (e.g., `10`, `-5`).
- **Floating Point (`float`)**: Decimal numbers (e.g., `3.14`, `2.5`).
- **Complex (`complex`)**: Numbers with real and imaginary parts (e.g., `3 + 4j`).

### Sequence Types
- **Strings (`str`)**: Ordered collection of characters.
  ```python
  name = "Python"
  ```
- **Lists (`list`)**: Ordered, mutable collection.
  ```python
  fruits = ["apple", "banana", "cherry"]
  ```
- **Tuples (`tuple`)**: Ordered, immutable collection.
  ```python
  coordinates = (10, 20)
  ```

### Set Types
- **Sets (`set`)**: Unordered, unique elements.
  ```python
  unique_numbers = {1, 2, 3, 3}
  ```

### Mapping Types
- **Dictionaries (`dict`)**: Key-value pairs.
  ```python
  student = {"name": "John", "age": 20}
  ```

## 12. Data Type Conversions
- `int()`, `float()`, `str()`, `list()`, `tuple()`, `set()`, `dict()`.
  ```python
  num = "10"
  num_int = int(num)  # Converts string to integer
  ```

## 13. Operators
- **Arithmetic**: `+`, `-`, `*`, `/`, `//`, `%`, `**`.
- **Comparison**: `==`, `!=`, `>`, `<`, `>=`, `<=`.
- **Logical**: `and`, `or`, `not`.
- **Bitwise**: `&`, `|`, `^`, `<<`, `>>`.
- **Assignment**: `=`, `+=`, `-=`, `*=`.

## 14. Control Flow Statements
### Conditional Statements
- **If-Else**:
  ```python
  age = 20
  if age > 18:
      print("Adult")
  else:
      print("Minor")
  ```

## 15. Loops
### For Loop
```python
for i in range(5):
    print(i)
```

### While Loop
```python
x = 0
while x < 5:
    print(x)
    x += 1
```

## 16. Pass Statement
- Used as a placeholder.
  ```python
  def my_function():
      pass
  ```

## 17. Continue Statement
- Skips the current iteration.
  ```python
  for i in range(5):
      if i == 2:
          continue
      print(i)
  ```

## 18. Comparison of Python with Other Languages
| Feature      | Python | C++ | Java |
|-------------|--------|-----|------|
| Syntax Simplicity | High | Medium | Medium |
| Speed | Slower | Faster | Faster |
| Memory Usage | High | Low | Medium |
| Multi-threading | Limited (GIL) | Good | Good |
| Libraries | Extensive | Moderate | Extensive |
