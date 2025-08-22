# 📘 Smart-Docs

Smart-Docs is an AI-powered document assistant that helps you **query, analyze, and summarize** documents like **PDFs, CSVs, and text files** using **state-of-the-art LLMs**.

Currently supports:
- **Gemini** (Google's Generative AI)  
- **Groq LLMs** (Fast inference with LLaMA / Mixtral)  

---

## 🚀 Features
- Extract insights from **PDFs, CSVs, and TXT files**
- Supports **similarity-based search** for document chunks
- Compare performance across **Gemini vs Groq**
- Modular notebooks for each file type

---

## 📂 Repository Structure

├── .gitignore

├── csv_gemini.ipynb # Query CSV with Gemini

├── csv_groq.ipynb # Query CSV with Groq

├── pdf_gemini.ipynb # Query PDF with Gemini

├── pdf_groq.ipynb # Query PDF with Groq

├── text_gemini.ipynb # Query text with Gemini

├── text_groq.ipynb # Query text with Groq

├── test.csv # Sample CSV file

├── Hamza_Personal_Profile.pdf # Sample PDF

├── intro.txt # Sample text file

## ▶️ Usage

Run the notebooks of your choice:

jupyter notebook pdf_gemini.ipynb

jupyter notebook pdf_groq.ipynb

jupyter notebook csv_gemini.ipynb

jupyter notebook text_groq.ipynb

(OR ANYOTHER)


## Each notebook demonstrates:

Loading documents

Chunking & embedding

Querying with Gemini or Groq

Summarization and similarity search

## ✨ Author

Built with ❤️ by Hamza



---

## ⚙️ Installation
Clone the repository and install requirements:

```bash
git clone https://github.com/MuhammadHamza123c/smart-docs.git
cd smart-docs
pip install -r requirements.txt
