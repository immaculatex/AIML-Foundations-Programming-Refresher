PERSONAL EXPENSE TRACKER
========================

Problem Statement:
------------------
In today’s fast-paced world, individuals need to track and manage their expenses effectively. 
This project provides a Personal Expense Tracker that allows users to log daily expenses, 
categorize them, and track spending against a monthly budget. 
The tracker also supports saving and loading expenses from a file for future reference.

Objectives:
-----------
1. Design and implement a personal expense tracker that enables users to manage their expenses.
2. Allow users to categorize expenses and set monthly budgets.
3. Implement file-handling functionality to save and load expense data.
4. Create an interactive, menu-driven interface for ease of use.

Features:
---------

1. Add Expense
   - Prompts the user to enter:
     * Date of the expense (YYYY-MM-DD)
     * Category (e.g., Food, Travel)
     * Amount spent
     * Description of the expense
   - Stores each expense as a record in a list.

2. View Expenses
   - Displays all stored expenses with validation.
   - Skips or notifies the user about incomplete data entries.

3. Set & Track Monthly Budget
   - Allows users to enter a monthly budget.
   - Tracks total spending and compares it with the budget.
   - Displays alerts if the budget is exceeded or shows remaining balance.

4. Save & Load Expenses
   - Saves all expenses to a CSV file for persistence.
   - Loads previous expenses automatically when the program starts.

5. Interactive Menu
   - Easy-to-use menu-driven system:
     1. Add Expense
     2. View Expenses
     3. Track Budget
     4. Save Expenses
     5. Exit

How to Run:
-----------
1. Clone the repository:
   git clone https://github.com/immaculatex/AIML-Foundations-Programming-Refresher.git

2. Navigate to the project directory:
   cd ExpenseTracker

3. Run the Python program:
   python CEP1_ExpenseTracker.ipynb

File Structure:
---------------
ExpenseTracker/
│
├── CEP1_ExpenseTracker.ipynb     - Main program
├── expenses.csv           - File to store saved expense data
└── README.txt             - Project documentation

Author:
--------
Immaculate Xavier
GitHub: https://github.com/immaculatex
