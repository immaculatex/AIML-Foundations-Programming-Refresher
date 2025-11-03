# ✅ Task Manager with User Authentication

## 📘 Problem Statement
In today’s world, individuals often need to keep track of various tasks in a structured way.  
This **Task Manager** allows users to create, view, update, and delete their tasks securely.  
Each user must log in with their own credentials, ensuring privacy and separation of data.  
Only the authenticated user can access their own tasks.

---

## 🎯 Objectives
1. Design and implement a user authentication system (login and registration).  
2. Create a task management system that allows users to:  
   - Add tasks  
   - View tasks  
   - Mark tasks as completed  
   - Delete tasks  
3. Use file handling to store user credentials and tasks persistently.  
4. Create an interactive, menu-driven interface for easy task management.

---

## 🧩 Features

### 1. 🔐 User Authentication
#### Registration:
- Prompts the user to enter a **username** and **password**.
- Ensures that the username is **unique**.
- **Hashes the password** for security before saving it to a file.

#### Login:
- Prompts the user for their username and password.
- Validates credentials against stored data.
- Grants access to the Task Manager upon successful login.

---

### 2. 📝 Add a Task
- Prompts the user for a **task description**.
- Assigns a **unique task ID** and sets the **status** to “Pending”.
- Stores the task in the user’s file.

Example:
```python
{'id': 1, 'description': 'Finish project report', 'status': 'Pending'}
