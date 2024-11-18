# 0x00. AirBnB clone - The console

# Description

This project is part of the ALX Software Engineering curriculum. It aims to build the foundational components of an AirBnB-like application, focusing on creating a command-line interface (CLI) to manage various objects related to the application, such as users, places, and reservations.

The primary objective is to practice object-oriented programming (OOP) concepts, file I/O, and the design of a system that mimics the core functionality of AirBnB but in a simplified form, using only Python.

# Requirements:
- Python 3.x
- No external libraries or frameworks are required.

---

# Command Interpreter

The command interpreter allows users to interact with the application by typing commands in a terminal. The interpreter reads input, processes commands, and performs various actions related to the application. The available commands are:

- `create <class_name>`: Create a new instance of the specified class (e.g., `create User`).
- `show <class_name> <id>`: Display an instance by its class name and ID (e.g., `show User 12345`).
- `destroy <class_name> <id>`: Delete an instance by class name and ID.
- `all <class_name>`: List all instances of a given class (e.g., `all User`).
- `quit`: Exit the program.

The interpreter mimics basic CRUD (Create, Read, Update, Delete) operations on various objects like `User`, `Place`, `City`, etc.

---

# How to Start

1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/airbnb_clone.git
   cd airbnb_clone

2. python3 console.py
