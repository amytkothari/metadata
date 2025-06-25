# 🧠 Metadata Generator

This project generates metadata from documents using local embedding models. It’s designed to be efficient, secure, and extendable.

---

## 📁 Folder Structure

```
metadata_generator/
├── .env                # API keys (excluded from GitHub)
├── metadata_generator.ipynb
├── requirements.txt
├── meta/               # Local files/data
├── chroma_db_temp/     # Temporary DB files
├── .gitignore
├── README.md
```

---

## ⚙️ Setup Instructions

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/metadata_generator.git
   cd metadata_generator
   ```

2. **Create virtual environment and install dependencies:**

   ```bash
   python -m venv venv
   venv\Scripts\activate  # Windows
   pip install -r requirements.txt
   ```

3. **Add your `.env` file manually (DO NOT upload it to GitHub):**

   ```
   GEMINI_API_KEY=your_api_key_here
   ```

---

## ✅ Tech Used

- Python 🐍
- Jupyter Notebook
- Gradio (optional)
- ChromaDB
- Local Embedding Model

---

## 🔐 Note
Your `.env` file is protected by `.gitignore`. Never share it or commit it!