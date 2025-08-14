# Code Review AI Assistant (DeepSeek-Coder)

This tool uses the **DeepSeek-Coder model** via Ollama to analyze code and provide feedback, suggestions, or bug fixes.

## 📌 Features

- **FastAPI** backend for processing and sending code to the AI model
- **Streamlit** frontend for a clean and interactive user interface
- **DeepSeek-Coder** model for intelligent code review
- Runs fully locally via **Ollama**

## 🚀 How to Run

### 1️⃣ Setup Environment

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
```

### 2️⃣ Pull Model

Make sure Ollama is installed and running:

```bash
ollama pull deepseek-coder
```

### 3️⃣ Start Backend

```bash
uvicorn backend.main:app --reload
```

### 4️⃣ Start Frontend

```bash
streamlit run frontend/app.py
```

### 5️⃣ Use the App

- Paste your code into the text area
- Click **Get Review**
- Receive AI-generated feedback, suggestions, and possible bug fixes

## 📂 Project Structure

```
code-review-deepseek/
├── backend/
│   └── main.py
├── frontend/
│   └── app.py
├── requirements.txt
└── README.md
```

## 🛠 Tech Stack

- Python
- FastAPI
- Streamlit
- Ollama (DeepSeek-Coder model)

---

## 🔗 Connect with Me

📧 kanishka96se@gmail.com  
🌐 [LinkedIn](https://www.linkedin.com/in/kanishka96/) | [GitHub](https://github.com/Kanishka96ac)
