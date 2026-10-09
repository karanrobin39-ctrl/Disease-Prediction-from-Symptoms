# 🏥 Disease Prediction from Symptoms Pipeline

An end-to-end Machine Learning diagnostics system designed to evaluate patient symptom matrices and predict potential clinical conditions.

---

## 🧬 Project Overview & Core Metrics

*   **Multi-Source Dataset Support:** Processes structured multi-label inputs from Kaggle alongside scraped text relational records from the Columbia University DBMI Knowledge Base.
*   **Agnostic Predictive Engine:** Features a comparative benchmarking architecture testing probabilistic, tree-based, and gradient-boosted topologies.
*   **Deterministic Feature Selection:** Standardizes 132 unique binary classification metrics to map deterministic patterns to target medical prognoses.

---

## 🛠️ Data Science & Modeling Tech Stack

*   **Runtime Environment:** Python 3.10+ (`requirements.txt` / Anaconda `environment.yml`)
*   **Configuration & EDA:** `config.yaml`, Pandas, NumPy
*   **Supervised Machine Learning:** Scikit-Learn
*   **Workspace Notebooks:** Jupyter Ecosystem (`demo.ipynb`)

---

## 🤖 Machine Learning Algorithms Explored

1.  **Naive Bayes Classifier:** Probabilistic baseline leveraging independent text token tracking.
2.  **Decision Tree Classifiers:** Hierarchical clinical triage boundaries.
3.  **Random Forest Ensemble:** Bootstrap aggregation across randomized trees.
4.  **Gradient Boosting Systems:** Sequential weak decision learner layers.

---

## 📊 Dataset Ingestion & Directory Blueprint

*   **Kaggle Source:** 133 distinct relational metric features ([Kaggle Link](https://kaggle.com)).
*   **Columbia University DBMI:** Unstructured text format mapping `Disease`, `Count`, and `Symptom` ([Columbia DBMI Link](https://columbia.edu)).

```text
├── dataset/                  # Relational cross-validation data records
├── notebook/                 # Prototyping workspace sandbox
├── saved_model/              # Pre-trained production binaries
├── config.yaml               # Runtime configurations
├── demo.ipynb                # Interactive exploration
├── infer.py                  # Standalone local evaluation
├── main.py                   # Model pipeline execution loop
└── requirements.txt          # Explicit pip framework dependency listing
```

---

## 🛠️ Installation & Reproduction Setup

```bash
# Clone repository and install dependencies
git clone https://github.com
cd Disease-Prediction-from-Symptoms
pip install -r requirements.txt

# Run training and inference loops
python main.py
python infer.py
```

---

## ⚠️ Medical & Operations Disclaimer
This system is a technical portfolio proof-of-concept. All outputs represent statistical probabilities and must never replace professional clinical diagnosis.

