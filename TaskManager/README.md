# 🧩 Task Manager & Expense Tracker

## 📘 Problem Statement

In today’s world, individuals often need to keep track of **tasks** and **expenses** in a structured and organized way.  
This project provides two simple yet powerful systems:

1. **Task Manager** – To manage daily tasks with authentication.  
2. **Expense Tracker** – To record expenses, manage budgets, and track spending.  

Both applications emphasize **file handling**, **data persistence**, and **menu-driven user interfaces** in Python.

---

## 🎯 Objectives

### Task Manager
1. Implement **User Authentication** (Login & Registration)
2. Allow users to:
   - Add, View, Mark as Completed, and Delete Tasks
3. Use **file handling** for storing credentials and tasks
4. Provide a **menu-driven interface** for task management

### Expense Tracker
1. Enable users to record and manage expenses
2. Track and compare spending against a **monthly budget**
3. Use **CSV files** for data storage and persistence
4. Offer an **interactive menu** for smooth navigation

---

## 🧑‍💻 Features & Functionalities

### 🔐 User Authentication

#### Registration:
- Prompts the user for a **username** and **password**.
- Ensures username uniqueness.
- **Hashes the password** before storing it securely in `users.csv`.

#### Login:
- Validates user credentials.
- On successful login, grants access to the **Task Manager** interface.
- Ensures that each user’s tasks remain **private and isolated**.

---

### 🧾 Task Manager Functionalities

#### 1. ➕ Add a Task
- Prompts the user to enter a **task description**.
- Assigns a **unique Task ID** and sets the status to `Pending`.
- Stores task details in a user-specific file, e.g., `tasks_<username>.csv`.

#### 2. 👀 View Tasks
- Displays all stored tasks for the logged-in user.
- Shows each task’s:
  - Task ID
  - Description
  - Status (`Pending` or `Completed`)

#### 3. ✅ Mark a Task as Completed
- Allows the user to select a task by **Task ID**.
- Updates its status to `Completed`.

#### 4. ❌ Delete a Task
- Enables the user to delete a specific task by **Task ID**.
- Confirms before removing it permanently from the task list.

#### 5. 🧭 Interactive Menu
A clean, text-based interface offering:
1. Add a Task  
2. View Tasks  
3. Mark a Task as Completed  
4. Delete a Task  
5. Logout  

The menu repeats until the user logs out.

---

## 💾 File Handling (Task Manager)

| File Name | Purpose |
|------------|----------|
| `users.json` | Stores registered usernames and hashed passwords |
| `<username>_tasks.json` | Stores user-specific tasks with Task ID, description, and status |

When a user logs in, the system automatically loads their existing tasks.

---