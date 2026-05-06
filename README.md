# 🧠 NLP: Spelling Correction & Cyberbullying Text Classification

A practical NLP repo containing **two end-to-end notebooks**:
1) **Spelling Correction System** (with optional Gradio demo)
2) **Cyberbullying / Text Classification** (classic ML pipeline)

Built to showcase real NLP workflow: preprocessing → feature extraction → modeling → evaluation.

---

## ✅ Projects

### 🔤 1) Spelling Correction System
What it does:
- Cleans & normalizes text
- Generates correction candidates
- Selects the best correction using scoring / ranking logic
- (Optional) Runs an interactive **Gradio** UI for quick testing



---

### 🛡️ 2) Cyberbullying / Text Classification
What it does:
- Text preprocessing (cleaning, tokenization, normalization)
- Vectorization (e.g., Bag-of-Words / TF-IDF)
- Model training with scikit-learn
- Evaluation (accuracy / precision / recall / F1)

Notebook: `notebooks/NLP_Khloud_Narjis(Text_classification).ipynb`

---

## 🧰 Tech Stack
Python • Jupyter • scikit-learn • NLP libraries (NLTK / spaCy) • Gradio (optional)

---

## 🚀 How to run locally

### 1) Create environment
```bash
python -m venv .venv
# Windows:
.venv\Scripts\activate
# macOS/Linux:
source .venv/bin/activate
2) Install dependencies
bash
Copy code
pip install -r requirements.txt
3) Launch notebooks
bash
Copy code
jupyter notebook
🎛️ Run the Gradio demo (if included in the notebook)
Open the spelling notebook and run the Gradio cell (usually near the end).
It will give you a local link like http://127.0.0.1:7860.

📁 Repository structure
txt
Copy code
.
├── notebooks/
├── requirements.txt
├── .gitignore
└── README.md
