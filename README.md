# EmojiCode

Welcome to the official documentation for the **EmojiCode** programming language! This is a custom programming language based on Python, where standard keywords and functions are replaced with emojis.

---

## Table of Contents
1. [Installation](#1-installation)
2. [Running Code](#2-running-code)
3. [Introduction](#3-introduction)
4. [Keywords](#4-keywords)
5. [Built-in Functions](#5-built-in-functions)
6. [Data Types](#6-data-types)
7. [Operators](#7-operators)
8. [Control Flow](#8-control-flow)
9. [Functions](#9-functions)
10. [File Handling](#10-file-handling)
11. [Example Code](#11-example-code)

---

## 1. Installation
Installation is very simple. Just copy the `translator.py` and `syntax.json` files into your project folder.

---

## 2. Running Code
You can run the code using a terminal with this command, assuming your file uses the `.ec` file extension:
`python translator.py <file name without extension>`

---

## 3. Introduction
EmojiCode uses the foundation of Python syntax but replaces keywords and built-in functions with emojis. This documentation provides a comprehensive guide to all replacements and usage examples.

---

## 4. Keywords
Here is the list of Python keywords and their EmojiCode equivalents:

- Python - EmojiCode
- `False`-`❌`
- `None`-`🚫`
- `True`-`✅`
- `and`-`🤝`
- `as`-`📎`
- `assert`-`📜`
- `async`-`⏩`
- `await`-`⏳`
- `break`-`🔨`
- `class`-`🏫`
- `continue`-`🔄`
- `def`-`📐`
- `del`-`🗑️`
- `elif`-`🔀`
- `else`-`🌈`
- `except`-`🚨`
- `finally`-`🏁`
- `for`-`🔁`
- `from`- `⬅️`
- `global`-`🌍`
- `if`-`❓`
- `import`-`📦`
- `in`-`📥`
- `is`-`🟩`
- `lambda`-`🧮`
- `nonlocal`-`📡`
- `not`-`🚷`
- `or`-`🔗`
- `pass`-`➡️`
- `raise`-`📈`
- `return`-`🔙`
- `try`-`🎯`
- `while`-`🔂`
- `with`-`📌`
- `yield`-`🌾`

---

## 5. Operators
Here is a list of Python's operators and their EmojiCode equivalents:

- Python - EmojiCode
- `+`-`➕`
- `-`-`➖`
- `/`-`➗`
- `//`-`🎵`
- `*`-`⭐`
- `**`-`✨`
- `%`-`📊`
- `<`-`⬅️`
- `>`-`➡️`
- `<=`-`📉⬅️`
- `>=`-`📈➡️`
- `=`-`🟰`
- `==`-`⚖️`
- `!=`-`🛑`
- `+=`-`📈`
- `-=`-`📉`

---

## 6. Built-in Functions
Here is a list of Python's built-in functions and their EmojiCode equivalents:

- Python - EmojiCode
- `print`-`🖨️`
- `input`-`🎤`
- `read`-`📖`
- `len`-`📏`
- `range`-`🎚️`
- `open`-`📂`
- `sum`-`☑️`
- `type`-`📄`

---

## 7. Data Types
The standard data types in Python remain unchanged in EmojiCode. However, you can still use the EmojiCode keywords and functions to work with these data types seamlessly.

---

## 8. Operators
EmojiCode uses the following operators:

- Python - EmojiCode
- `and`-`🤝`
- `or`-`🔗`
- `not`-`🚷`
- `is`-`🟩`
- `in`-`📥`

---

## 9. Control Flow
Control flow in EmojiCode works as follows:

- Python - EmojiCode
- `if`-`❓`
- `elif`-`🔀`
- `else`-`🌈`
- `for`-`🔁`
- `while`-`🔂`
- `break`-`🔨`
- `continue`-`🔄`
- `pass`-`➡️`

---

## 10. Functions
Functions are defined using `📐` and can return values using `🔙`.

Example:
```
📐 Main():
    🔙 10
```

---

## 11. File Handling
Use `📂` to open files in EmojiCode.

Example:
```
📌 📂(file_name) 📎 file:
    text = file.📖()
```

---

## 12. Example Code
Example 1:  
EmojiCode:
```
📦 sys

🔁 name 📥 ["Alice", "Bob", "Charlie"]:
    🖨️(f"Hello, {name}!")
    ❓ name ⚖️ "Bob":
        🖨️("You found Bob!")

🔁 i 📥 🎚️(5):
    🖨️(f"Count: {i}")
```

Python:
```
import sys

for name in ["Alice", "Bob", "Charlie"]:
    print(f"Hello, {name}!")
    if name == "Bob":
        print("You found Bob!")

for i in range(5):
    print(f"Count: {i}")
```

Example 2:  
EmojiCode:
```
📦 time

📐 countdown(time_sec):
    🔂 time_sec:
        mins, secs 🟰 divmod(time_sec, 60)
        timeformat 🟰 '{:02d}:{:02d}'.format(mins, secs)
        🖨️(timeformat, end='\r')
        time.sleep(1)
        time_sec 📉 1

    🖨️("stop")

countdown(5)
```

Python:
```
import time

def countdown(time_sec):
    while time_sec:
        mins, secs = divmod(time_sec, 60)
        timeformat = '{:02d}:{:02d}'.format(mins, secs)
        print(timeformat, end='\r')
        time.sleep(1)
        time_sec -= 1

    print("stop")

countdown(5)
```

---

## 13. Custom Syntax
You can edit the EmojiCode keywords by modifying the `syntax.json` file.

---