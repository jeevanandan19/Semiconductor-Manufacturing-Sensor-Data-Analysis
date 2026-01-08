# Intelligent Research Paper Summarizer with Novelty Detection

## 📌 Project Overview
The **Intelligent Research Paper Summarizer with Novelty Detection** is an NLP-based capstone project designed to assist researchers, students, and academicians in quickly understanding research papers and evaluating their originality.

The system automatically extracts text from research papers, generates concise summaries using transformer models, and detects the novelty of a paper by comparing it with related research from trusted academic sources.

---

## 🎯 Objectives
- Automatically extract text from research papers (PDF/DOCX)
- Generate meaningful summaries using NLP transformer models
- Retrieve related research papers from online sources
- Measure semantic similarity and compute novelty score
- Highlight novel concepts and contributions

---

## 🧠 Key Features
- 📄 Upload research papers (PDF/DOCX)
- ✂️ Automatic text preprocessing and cleaning
- 📝 Transformer-based summarization
- 🔍 Semantic similarity comparison
- 📊 Novelty score calculation
- 🌐 Web-based interface using Flask

---

## 🔍 Data Sources
The system fetches related research papers from:
- Semantic Scholar
- arXiv
- OpenAlex

Each source is assigned a credibility weight to improve novelty scoring accuracy.

---

## 🧠 Methodology
1. User uploads a research paper
2. Text is extracted and preprocessed
3. Summary is generated using transformer models
4. Related papers are fetched using APIs
5. Sentence embeddings are computed
6. Semantic similarity is calculated
7. Novelty score is generated and displayed

---

## 🛠️ Technologies Used
- **Programming Language:** Python
- **Web Framework:** Flask
- **NLP Libraries:**
  - Transformers
  - Sentence-Transformers
  - NLTK
  - Scikit-learn
- **Other Tools:**
  - PDFPlumber
  - BeautifulSoup
  - ThreadPoolExecutor
- **Environment:** Jupyter Notebook

---

## 📂 Project Structure
```
Capestone2.ipynb
app.py
templates/
static/
.env
requirements.txt
```

---

## 🚀 How to Run the Project
1. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
2. Run the Flask application:
   ```bash
   python app.py
   ```
3. Open browser and navigate to:
   ```
   http://127.0.0.1:5000/
   ```

---

## 📊 Output
- Research paper summary
- Similar research papers list
- Novelty percentage score
- Highlighted novel terms

---

## 📌 Applications
- Academic research assistance
- Literature review automation
- Research originality checking
- University and institutional research support

---

## ✨ Future Enhancements
- Citation-level novelty detection
- Plagiarism-aware novelty scoring
- Interactive dashboards
- Multi-language research paper support

---

## 👤 Author
**Jeevanandan V**

---

## 📄 License
This project is developed for academic and educational purposes only.
