# Mongodb-Zen-class-programme
# Zen Class Programme - MongoDB Project

This project sets up and queries a MongoDB database to manage and analyze data for the Zen Class programme. It includes collections for users, codekata problems, attendance, topics, tasks, company drives, and mentors.

---

## 📂 Collections

- `users`: Stores student information.
- `codekata`: Tracks problems solved by each user.
- `attendance`: Records daily attendance for students.
- `topics`: Lists all topics taught in the class.
- `tasks`: Assignments linked to topics and students.
- `company_drives`: Company placement drive details.
- `mentors`: Mentor details with assigned mentees.

---

## 📦 Setup Instructions

1. **Install MongoDB** if not already installed:  
   [MongoDB Installation Guide](https://docs.mongodb.com/manual/installation/)

2. **Open MongoDB Shell** or **MongoDB Compass Playground**.

3. **Switch to the database:**
   ```js
   use zen_class_programme;
