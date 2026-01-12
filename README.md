<p align="center">
  <a href="" rel="noopener">
 <img width=200px height=200px src="https://pythonistaplanet.com/wp-content/uploads/2023/04/How-to-Use-ChatGPT-with-Python-%E2%80%93-An-Easy-Guide.jpg" alt="Project logo"></a>
</p>

<h3 align="center">Python Debugging with AI</h3>

<div align="center">

[![Status](https://img.shields.io/badge/status-active-success.svg)]()
[![Language](https://img.shields.io/badge/language-Python-blue.svg)]()
[![Level](https://img.shields.io/badge/level-beginner-brightgreen.svg)]()
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](/LICENSE)

</div>

---

<p align="center">
  Introduction to Python debugging for beginners, using Artificial Intelligence as a learning and assistance tool.
  <br>
</p>

## 📝 Table of Contents

- [About](#about)
- [Getting Started](#getting_started)
- [Usage](#usage)
- [Examples](#examples)
- [Built Using](#built_using)
- [Authors](#authors)
- [Acknowledgments](#acknowledgement)

---

## 🧐 About <a name="about"></a>

This project is designed for **Python beginners** who want to learn how to **debug code effectively**.  
It focuses on understanding common Python errors (syntax errors, runtime errors, logic errors) and how to fix them.

A key aspect of this project is the **use of Artificial Intelligence (ChatGPT)** as a debugging assistant to:
- Understand error messages
- Identify bugs
- Suggest corrections
- Improve code logic

The goal is not to rely blindly on AI, but to **learn how to reason about errors** with its help.

---

## 🏁 Getting Started <a name="getting_started"></a>

These instructions will help you run the scripts locally and understand common debugging scenarios.

### Prerequisites

You need:
- Python 3.x installed
- A Linux environment (Ubuntu recommended)
- Basic knowledge of terminal commands

Check Python installation:
```bash
python3 --version
Installing
Clone the repository:

bash
Copier le code
git clone https://github.com/your-username/python-debugging-ai.git
cd python-debugging-ai
Make scripts executable if needed:

bash
Copier le code
chmod +x *.py
🎈 Usage <a name="usage"></a>
Run a Python script:

bash
Copier le code
python3 script.py
Or, if executable:

bash
Copier le code
./script.py
When an error occurs:

Read the traceback

Identify the error type

Use AI to help explain the error

Fix and test again

🧪 Examples <a name="examples"></a>
Example of a common error:

python
Copier le code
while n > 1:
    result *= n
Problem:

Infinite loop because n is never decremented

Fix:

python
Copier le code
while n > 1:
    result *= n
    n -= 1
Another example:

bash
Copier le code
IndexError: list index out of range
Cause:

Missing command-line argument

⛏️ Built Using <a name="built_using"></a>
Python 3 - Programming language

Linux - Development environment

ChatGPT - AI debugging assistant

✍️ Authors <a name="authors"></a>
darkkem - Python beginner & learner

🎉 Acknowledgements <a name="acknowledgement"></a>
Holberton School

Python documentation

ChatGPT for debugging guidance and explanations

yaml
