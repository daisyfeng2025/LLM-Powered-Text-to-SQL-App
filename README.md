# Gemini SQL Agent — Natural Language to SQL

This project is an interactive AI-powered SQL assistant built using **Google Gemini 1.5 Pro**, capable of translating natural language questions into executable SQL queries. It leverages **Streamlit** for the user interface and **SQLite** for the underlying data storage, allowing users to query structured data with zero SQL knowledge.

---

## Key Features

- Ask questions in plain English — get instant SQL answers
- Uses `gemini-1.5-pro-latest` for text generation
- Executes live SQL queries on a local `student.db` SQLite database
- Uses `.env` file for secure API key management
- Displays query results dynamically in the browser via Streamlit

---

## Tech Stack

- **Frontend:** Streamlit
- **Backend:** Python 3.10+, SQLite
- **AI Model:** Google Generative AI (Gemini)
- **Environment Management:** `dotenv`
- **Deployment Option:** Streamlit Cloud / Localhost

---

## Example Use Cases

- "How many students are in the database?" → SELECT COUNT(*) FROM STUDENT;
- "List all students in the Data Science class." → SELECT * FROM STUDENT WHERE CLASS = 'Data Science';
