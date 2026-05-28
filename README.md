# 💊 AI Agent Farmasi

AI Agent Farmasi adalah aplikasi chatbot berbasis AI yang menggunakan pendekatan Retrieval-Augmented Generation (RAG) untuk memberikan informasi obat secara lebih relevan dan kontekstual.

Aplikasi ini dibangun menggunakan:

* Streamlit
* FAISS Vector Database
* Sentence Transformers
* OpenRouter LLM API
* Python

---

# ✨ Features

* Semantic search obat menggunakan embedding
* AI chatbot farmasi interaktif
* Retrieval menggunakan FAISS
* Streamlit chat UI
* Multi-language embedding model
* Context-aware response
* Environment variable security menggunakan `.env`

---

# 🧠 Tech Stack

| Technology            | Description              |
| --------------------- | ------------------------ |
| Python                | Backend language         |
| Streamlit             | Web interface            |
| FAISS                 | Vector similarity search |
| Sentence Transformers | Text embedding           |
| OpenRouter API        | Large Language Model     |
| Pandas                | Data processing          |
| NumPy                 | Numerical computation    |

---

# 📁 Project Structure

```text
AI-Agent-Farmasi/
│
├── pharmacy_ai.py
├── streamlit_app.py
├── requirements.txt
├── .gitignore
├── .env
│
├── models/
│   ├── faiss_index.index
│   └── data_obat.pkl
```

---

# ⚙️ Installation

## 1. Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/drugs-ai.git
```

## 2. Masuk ke Folder Project

```bash
cd drugs-ai
```

## 3. Install Dependencies

```bash
pip install -r requirements.txt
```

---

# 🔑 Environment Variables

Buat file `.env`

```env
OPENROUTER_API_KEY=your_api_key_here
```

---

# ▶️ Run Application

```bash
streamlit run streamlit_app.py
```

---

# 💬 Example Questions

* Obat untuk luka bakar ringan
* Obat untuk sakit kepala
* Efek samping paracetamol
* Kontraindikasi ibuprofen
* Obat flu yang aman

---

# 🔒 Safety Notes

Aplikasi ini:

* Tidak memberikan diagnosis medis
* Tidak menggantikan konsultasi dokter
* Tidak memberikan resep medis
* Hanya memberikan informasi berdasarkan dataset obat yang tersedia

---

# 🚀 Future Improvements

* Streaming response seperti ChatGPT
* Citation/source references
* Reranking retrieval
* Chat memory
* Voice assistant
* Authentication system
* Docker deployment
* Cloud deployment
* Medical safety guardrails

---

# 📌 Author

Developed by Judo Dama

---

# 📄 License

This project is for educational and research purposes.
