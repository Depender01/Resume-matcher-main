# 🤖 Resume Matcher

A FastAPI-based web application that automatically evaluates and scores resumes (PDFs) against a provided job description using multiple matching methods: GPT, cosine similarity, keyword matching, and a custom hybrid algorithm.

---

## 🚀 Features
- 📤 Upload multiple PDF resumes  
- 📝 Upload or paste a job description  
- 🧠 Select matching method: `gpt`, `cosine`, or `hybrid`  
- 📊 View similarity scores with explanation  
- 📁 Download top N resumes as a ZIP  
- 📌 Boost score if resume meets experience requirement  

---

## 🧠 Matching Algorithms
- **GPT Match:** Uses OpenAI’s GPT API to score resumes  
- **Cosine Match:** Uses TF-IDF & cosine similarity  
- **Keyword Match:** Basic keyword overlap  
- **Hybrid Match:** Weighted combination of all above + experience  

---

## 🛠️ Tech Stack
- **Backend:** FastAPI  
- **Frontend:** Jinja2 Templates  
- **PDF Parsing:** PyMuPDF  
- **Embedding/Similarity:** scikit-learn, sentence-transformers  
- **LLM:** OpenAI (GPT-3.5/4 via API)  
- **Deployment:** Railway / Render / Fly.io (custom domain ready)  

---

## 📂 Project Structure
