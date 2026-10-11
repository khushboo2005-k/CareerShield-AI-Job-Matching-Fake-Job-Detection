# CareerShield-AI-Job-Matching-Fake-Job-Detection
CareerShield AI is an intelligent job matching and fake job detection system that combines Machine Learning, Deep Learning, and Natural Language Processing (NLP) to identify potentially fraudulent job postings and help job seekers find relevant career opportunities.
# 🛡️ CareerShield AI

### Intelligent Job Matching & Fake Job Detection System

CareerShield AI is an AI-powered project designed to help job seekers identify potentially fraudulent job postings and discover suitable career opportunities using Machine Learning, Deep Learning, and Natural Language Processing (NLP).

## 🎯 Project Objectives

- Detect potentially fraudulent job postings.
- Compare traditional Machine Learning models.
- Explore transformer-based Deep Learning using DistilBERT.
- Match resumes with relevant job descriptions.
- Identify missing skills and career development opportunities.
- Evaluate model generalization on unseen company job postings.

## 🧠 Technologies Used

- Python
- Pandas and NumPy
- Scikit-learn
- TF-IDF and NLP
- Logistic Regression
- Linear Support Vector Machine (SVM)
- DistilBERT
- Hugging Face Transformers
- Google Colab
- Streamlit (planned for deployment)

## ⚙️ Key Features

### 1. Fake Job Detection
Analyzes job descriptions to classify postings as potentially fraudulent or likely legitimate.

### 2. Machine Learning Model Comparison
Evaluates classification models using precision, recall, F1-score, and ROC-AUC.

### 3. Deep Learning
Explores DistilBERT for contextual text classification.

### 4. Generalization Testing
Uses unseen-company evaluation and grouped cross-validation to investigate how well models perform on unfamiliar job postings.

### 5. AI Career Matching
Planned functionality to extract resume skills, recommend relevant jobs, and identify skill gaps.

## 📊 Initial Machine Learning Results

The Logistic Regression model achieved the following results in the current unseen-company test experiment:

| Metric | Score |
|---|---:|
| Accuracy | 94.75% |
| Precision | 67.48% |
| Recall | 60.43% |
| F1-score | 63.76% |
| ROC-AUC | 92.40% |

These are preliminary results from one evaluation setup, not a guarantee of real-world performance. Additional validation and Deep Learning comparisons are in progress.

## 📂 Project Structure

```text
CareerShield-AI/
├── notebooks/
│   └── careershield_experiments.ipynb
├── models/
├── app/
│   └── streamlit_app.py
├── results/
│   └── model_comparison.csv
├── requirements.txt
└── README.md
```

*Note: This is a proposed structure. Add files as they are created; do not include empty or nonexistent files as completed components.*

## 🚀 Current Development Status

- [x] Dataset preprocessing
- [x] Initial Machine Learning training
- [x] Grouped cross-validation experiment
- [x] Initial unseen-company evaluation
- [ ] DistilBERT evaluation
- [ ] Resume parsing and skill extraction
- [ ] Semantic job matching
- [ ] Streamlit dashboard
- [ ] Independent external dataset validation

## ⚠️ Disclaimer

Predictions are estimates based on available data and should not be treated as proof that a job or employer is fraudulent. Verify employers independently before sharing personal information or paying any fees.

## 👩‍💻 Author

**Khushboo Amrat Kumar**

Data Science | Machine Learning | Deep Learning | NLP

## 📜 License

This project can be released under the MIT License after adding a `LICENSE` file and confirming that the dataset and dependencies permit the intended use.
