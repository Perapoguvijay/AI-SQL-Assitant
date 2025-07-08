# AI-SQL-Assitant
# 🧠 Gemini SQL Assistant (Streamlit + SQLite + Gemini API)

This project is an AI-powered SQL assistant that translates natural language questions into SQL queries and runs them on a local SQLite database using Google's **Gemini API** and **Streamlit**.

It allows users—both technical and non-technical—to interact with a database using plain English and receive instant results, with SQL query explanations included.

---

## 🚀 Features

- 🔹 **Natural Language to SQL** using Gemini 2.0 Flash LLM.
- 🔹 Executes queries directly on a local **SQLite** database.
- 🔹 Provides clear, step-by-step **explanations** for each generated SQL query.
- 🔹 Easy-to-use, responsive **Streamlit web UI**.
- 🔹 Built-in **prompt engineering** for improved query accuracy.

---

## 🛠️ Tech Stack

- **Python**
- **Streamlit** – for building the interactive UI
- **SQLite** – lightweight local database
- **Google Generative AI (Gemini)** – for SQL generation and explanation
- **dotenv** – to manage API keys securely

---

## 📁 Database Schema Used

Database: `Naresh_it_employee1.db`  
Table: `Naresh_it_employee1`

| Column Name      | Data Type |
|------------------|-----------|
| employee_name    | TEXT      |
| employee_role    | TEXT      |
| employee_salary  | FLOAT     |

---

## 🖼️ UI Screenshots

> Add your own screenshots here to demonstrate the app in action.

---

## ⚙️ Setup Instructions

### 1. Clone the Repo

```bash
git clone https://github.com/yourusername/gemini-sql-assistant.git
cd gemini-sql-assistant
