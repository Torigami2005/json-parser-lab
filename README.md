# 🧾 JSON Parser Lab (Docker + Python)

## 📌 Overview
This project is a Python-based JSON parser that reads and processes student enrollment data from a JSON file. It is containerized using Docker to ensure a consistent runtime environment across different systems.

The program demonstrates:
- JSON parsing
- File handling
- Data processing
- Summary report generation
- Docker containerization

---

## 📁 Project Structure

JSON-PARSER-LAB/
│
├── data/
│ └── students.json
│
├── src/
│ └── parse_json.py
│
├── Dockerfile
├── .gitignore
└── README.md


---

## 🚀 Features
- Load and parse JSON student data
- Display school information
- Display student records with enrolled courses
- Calculate total units per student
- Compute:
  - Total students
  - Total courses offered
  - Average units per student
- Filter BS Information Technology students
- Error handling for missing/invalid JSON files

---

## 🧠 How It Works
1. The program reads `students.json` from the `data/` folder.
2. It parses JSON data into Python dictionaries and lists.
3. It processes each student:
   - Displays personal details
   - Lists enrolled courses
   - Calculates total units
4. It generates a summary report:
   - Total students
   - Total courses
   - Average units per student
   - BS Information Technology students only

---

## 🐳 Running with Docker

### 🔨 Build the Docker image
```bash
docker build -t json-parser-lab .