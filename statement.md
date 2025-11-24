# Problem Statement

## The Problem
Students and working adults often struggle with managing their pocket money and maintaining a healthy lifestyle. We often spend money without tracking it and neglect sleep or diet. It is difficult to keep track of everything using just notebooks or memory.

## The Solution
I created a simple command-line interface (CLI) program using Python called **LifeHUD**. It helps a user:
1. **Manage Finances:** Store current wallet balance and track daily expenses/income.
2. **Track Health:** Calculate a "Health Score" based on daily habits like sleep and diet.
3. **Save Data:** The program uses a JSON file to automatically save all data, so nothing is lost when the application closes.

This tool solves the problem of data loss in simple calculators and provides a single place to manage student life.

# Scope of the Project :
## In-Scope (What the project does)
* **Single-User Management:** The system is designed for a single user to track their personal data on their local machine.
* **Data Persistence:** All inputs (name, wallet balance, health stats) are saved permanently in a JSON file so data is not lost after closing the program.
* **Manual Entry:** The user manually inputs their daily expenses and health ratings via the command line.
* **Basic Analysis:** The system performs simple calculations to update the wallet balance and generate a daily health score (0-100).

## Out-of-Scope (What is not included in this version)
* **Graphical User Interface (GUI):** The project currently runs only in the terminal/console.
* **Bank Integration:** It does not connect to real bank accounts or fetch transactions automatically.
* **Multi-User Support:** It does not support multiple accounts or passwords in this version.
* **Visual Graphs:** It does not display charts or graphs for spending history.

# Target Users:
College student , working adults who find documenting their health and expenses difficult and a headache.
