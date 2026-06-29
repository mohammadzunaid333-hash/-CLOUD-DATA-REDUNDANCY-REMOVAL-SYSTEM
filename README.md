# ☁️ Cloud Data Redundancy Removal System

A modern full-stack web application that detects and removes duplicate records before storing them in the database. Built using **FastAPI, SQLite, HTML, CSS, and JavaScript**, this project demonstrates CRUD operations, REST APIs, and database integration.

---

## 📌 Project Overview

The Cloud Data Redundancy Removal System helps maintain clean and organized data by preventing duplicate entries.

Users can:
- Add new records
- Prevent duplicate email entries
- Search records instantly
- Delete records
- Export records to CSV
- Monitor database status

---

## ✨ Features

- ✅ Add New Records
- ✅ Duplicate Email Detection
- ✅ Live Search (Name & Email)
- ✅ Delete Records
- ✅ Export Records to CSV
- ✅ SQLite Database Integration
- ✅ REST API using FastAPI
- ✅ Responsive Modern UI
- ✅ Database Status Indicator
- ✅ Total Records Counter

---

## 🛠 Tech Stack

### Frontend
- HTML5
- CSS3
- JavaScript

### Backend
- FastAPI
- Python

### Database
- SQLite

---

## 📂 Project Structure

```
Cloud-Data-Redundancy-Removal-System/
│
├── app.py
├── database.py
├── data.db
├── index.html
├── style.css
├── script.js
└── README.md
```

---

## 🚀 Installation

### 1. Clone Repository

```bash
git clone https://github.com/mohammadzunaid333-hash/-CLOUD-DATA-REDUDANCY-REMOVAL-SYSTEM.git
```

### 2. Open Project

```bash
cd -CLOUD-DATA-REDUDANCY-REMOVAL-SYSTEM
```

### 3. Install Dependencies

```bash
pip install fastapi uvicorn
```

### 4. Start Backend

```bash
uvicorn app:app --reload
```

Backend URL

```
http://127.0.0.1:8000
```

### 5. Run Frontend

Open `index.html` using Live Server in VS Code.

---

## 🔗 API Endpoints

| Method | Endpoint | Description |
|---------|----------|-------------|
| GET | `/` | API Status |
| GET | `/records` | Get All Records |
| POST | `/add-record` | Add Record |
| DELETE | `/delete-record/{email}` | Delete Record |
| GET | `/status` | Database Status |

---





```

```

---

## ⚙️ How It Works

1. User enters Name and Email.
2. Backend checks if the email already exists.
3. Duplicate records are rejected.
4. Unique records are stored in SQLite.
5. Records are displayed instantly.
6. Users can search, delete, or export records.

---

## 🚀 Future Enhancements

- User Authentication
- Cloud Database Integration
- User Roles & Permissions
- Bulk CSV Upload
- Dashboard Analytics
- Data Encryption
- Email Verification

---

## 👨‍💻 Author

**Pinjari Mohammed Zunaid**

- 🎓 B.Tech CSE (AI & DS)
- 🏫 Mohan Babu University
- 💻 Aspiring Data Analyst & Full Stack Developer

GitHub:
https://github.com/mohammadzunaid333-hash

---

## ⭐ Support

If you found this project helpful, consider giving it a **⭐ Star** on GitHub.

---

## 📄 License

This project is developed for educational and internship purposes.
