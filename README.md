# Operations-automation

This project is designed to help individuals automate daily tasks, send reminders, and keep a log of completed tasks efficiently. It demonstrates both **task management** and **automation skills** using Python.

---

## Features
**Task Automation System (Notebook + CLI)**
   - Add new tasks dynamically.
   - Run task reminders with configurable delay.
   - Logs completed tasks with timestamps.
   - Stores tasks persistently in a text file.

1. **Interactive Notebook**
   - Load existing tasks and add new ones interactively.
   - Run task reminders inside Jupyter Notebook.

2. **Command-Line Interface (CLI)**
   - Add tasks from terminal.
   - Run tasks with optional delay.
   - Simple and easy-to-use CLI for daily operations.

---

## Tools Used
- Python  
- `time` module for delay simulation  
- CSV/text file for task storage  

---

## How to Run

- Open `OperationsAutomation.ipynb` in Jupyter Notebook or Google Colab and run cells step by step.  
- Or use CLI commands:  
  - Add tasks: `python cli.py --add "Task1" "Task2"`  
  - Run tasks: `python cli.py --run`  
  - Run with custom delay: `python cli.py --run --delay 3`  

---

## Outcome
- Automates daily task reminders efficiently.  
- Maintains a log of completed tasks.  
- Provides a simple workflow system via Notebook or CLI.  
