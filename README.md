# 🏗️ SiteSense AI — Construction Intelligence Platform

An AI-powered construction intelligence platform designed to help users explore construction-related information through a modern web interface and Python backend.

## 📌 Overview

**SiteSense AI** is a full-stack web application built with React and FastAPI. It provides a foundation for integrating intelligent construction workflows through a responsive frontend and REST API backend.

## ✨ Features

- ⚛️ React-based user interface
- ⚡ FastAPI backend and REST API
- 🐍 Python backend services
- 📄 Interactive API documentation with Swagger UI
- 🔌 Frontend and backend separation for easier development
- 🤖 OpenAI integration support for AI-powered functionality

> Note: Available features depend on the current implementation and configuration.

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Frontend | React, Vite, JavaScript, CSS |
| Backend | Python, FastAPI |
| API Server | Uvicorn |
| Validation | Pydantic |
| AI Integration | OpenAI API (optional) |
| Version Control | Git, GitHub |

## 📂 Project Structure

```text
SiteSense-AI/
├── backend/
│   ├── app/
│   │   ├── __init__.py
│   │   ├── main.py
│   │   ├── schemas.py
│   │   └── services.py
│   ├── requirements.txt
│   └── .env.example
├── frontend/
│   ├── src/
│   │   ├── App.jsx
│   │   ├── main.jsx
│   │   └── styles.css
│   ├── index.html
│   ├── package.json
│   └── package-lock.json
├── .gitignore
└── README.md
```

## ⚙️ Prerequisites

Install the following before running the project:

- Python
- Node.js and npm
- Git

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/himanshi-jain20/SiteSense-AI.git
cd SiteSense-AI
```

### 2. Set up the backend

Open a terminal in the project root:

```bash
cd backend
python -m venv .venv
```

Activate the virtual environment on Windows:

```powershell
.\.venv\Scripts\Activate.ps1
```

Install the Python dependencies:

```bash
python -m pip install -r requirements.txt
```

Start the backend server:

```bash
python -m uvicorn app.main:app --reload
```

Backend API: http://127.0.0.1:8000

Interactive API documentation: http://127.0.0.1:8000/docs

### 3. Set up the frontend

Open a **second terminal** from the project root:

```bash
cd frontend
npm install
npm run dev
```

Open the local URL printed by Vite, usually:

http://localhost:5173

Keep both terminals running while using the application.

## 🔐 Environment Configuration

If AI functionality requires an API key, configure it locally using the environment variables expected by the backend.

- Never commit API keys, passwords, or private credentials.
- Use `.env.example` as a reference if it documents the required variables.
- Keep your actual `.env` file out of Git.

## 📸 Screenshots

Add screenshots of the running application here.

Suggested screenshots:
- Main dashboard
- Construction analysis interface
- API documentation

For example, save images in a `screenshots/` folder and embed them using:

```markdown
![SiteSense AI Dashboard](screenshots/dashboard.png)
```

## 🗺️ Future Improvements

Potential enhancements include:

- Construction image analysis
- AI-assisted construction insights
- Project progress tracking
- Construction risk identification
- Reporting and analytics dashboard

These are roadmap ideas, not claims that every feature is already implemented.

## 🤝 Contributing

Contributions, suggestions, and bug reports are welcome. Open an issue to discuss improvements or propose a change.

## 👩‍💻 Author

**Himanshi Jain**

GitHub: [@himanshi-jain20](https://github.com/himanshi-jain20)

## 📄 License

No license has been specified yet. Add a suitable license file if you intend to permit others to reuse or distribute this project.
