# FUTURE_ML_02 — Support Ticket Classification
### Future Interns — Machine Learning Internship | Task 2 | 2026

---

## 📌 Project Overview
An end-to-end NLP pipeline to automatically classify IT support tickets
into categories and assign priority levels using machine learning.

---

## 📊 Dataset
| Attribute | Detail |
|---|---|
| **Name** | IT Service Ticket Classification Dataset |
| **Source** | Kaggle |
| **Total Tickets** | 47,837 |
| **Categories** | 8 |
| **Priority Levels** | 4 |

---

## 🛠️ Tools & Libraries
| Tool | Purpose |
|---|---|
| **Python** | Core language |
| **Jupyter Notebook** | Development environment |
| **NLTK** | Text cleaning, tokenization, lemmatization |
| **Scikit-learn** | TF-IDF, ML models, evaluation |
| **Pandas, NumPy** | Data processing |
| **Matplotlib, Seaborn** | Visualisation |

---

## ⚙️ Key Features
- Text cleaning & tokenization using NLTK
- Stopword removal & lemmatization
- TF-IDF vectorization (5,000 features, bigrams)
- Rule-based priority tagging system
- Multi-class ticket classification

---

## 🤖 Models Trained
| Model | Accuracy | F1 Score |
|---|---|---|
| **Logistic Regression ✅** | **85.19%** | **0.8519** |
| Random Forest | 84.17% | 0.8417 |
| Naive Bayes | 78.03% | 0.7784 |

---

## 🚨 Priority Classification
| Model | Accuracy | F1 Score |
|---|---|---|
| **Logistic Regression ✅** | **92.64%** | **0.9242** |

---

## 📊 Category Results
| Category | Precision | Recall | F1 |
|---|---|---|---|
| Access | 0.92 | 0.88 | 0.90 |
| Admin Rights | 0.88 | 0.62 | 0.73 |
| HR Support | 0.86 | 0.87 | 0.86 |
| Hardware | 0.79 | 0.88 | 0.83 |
| Internal Project | 0.93 | 0.82 | 0.87 |
| Miscellaneous | 0.82 | 0.82 | 0.82 |
| Purchase | 0.97 | 0.86 | 0.91 |
| Storage | 0.93 | 0.82 | 0.87 |

---

## 🧠 Key Findings
- Hardware tickets most common (28.5%)
- Purchase tickets highest precision (0.97)
- Low priority tickets predicted perfectly (recall=1.00)
- Logistic Regression best model for both tasks
- TF-IDF + NLP achieves 85% category accuracy
- Priority system achieves 92% accuracy

---

## 📂 Project Structure
FUTURE_ML_02/
├── FUTURE_ML_02(Support Ticket Classification).ipynb
├── all_tickets_processed_improved_v3.csv
├── eda_overview.png
├── eda_analysis.png
├── eda_insights.png
├── model_comparison.png
├── confusion_matrix.png
├── priority_confusion_matrix.png
└── README.md
---

## 📚 Internship Details
| Field | Detail |
|---|---|
| **Organization** | Future Interns |
| **Domain** | Machine Learning |
| **CIN** | FIT/APR26/ML7297 |
| **Period** | 24/04/2026 – 24/05/2026 |

---

## 👤 Author
**Syed Nadimul Haque**
Data Scientist | Machine Learning Engineer| AI Engineer| Software Engineer
🔗 LinkedIn: linkedin.com/in/your-profile

