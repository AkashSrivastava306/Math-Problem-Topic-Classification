# 🧠 Math Problem Topic Classification

This project focuses on **classifying math problems into specific topics** using NLP and machine learning techniques. The dataset includes natural language math questions categorized into one of eight predefined math topics.

## 📁 Dataset Description
📌 **Source:** [Kaggle Competition – Classification of Math Problems](https://www.kaggle.com/competitions/classification-of-math-problems-by-kasut-academy/overview)

The dataset consists of the following files:

- `train.csv`: ~10,000 labeled math questions
- `test.csv`: ~3,000 unlabeled math questions

Each question is expressed in natural language, such as:

> _"Find the real solutions to x² - 5x + 6 = 0."_

### 🔖 Topic Labels

| Label | Topic                            |
|-------|----------------------------------|
| 0     | Algebra                          |
| 1     | Geometry and Trigonometry        |
| 2     | Calculus and Analysis            |
| 3     | Probability and Statistics       |
| 4     | Number Theory                    |
| 5     | Combinatorics and Discrete Math |
| 6     | Linear Algebra                   |
| 7     | Abstract Algebra and Topology   |

---

## 📊 Model & Approach

The notebook implements an NLP-based classification pipeline using:

- Text cleaning and preprocessing
- TF-IDF feature extraction
- Classification models such as Logistic Regression,SVM and XGBoost
- Hyperparameter tuning and evaluation
- Submission formatting for Kaggle

Achieved a **private leaderboard score of `0.7711`** on Kaggle.

---


🛠 Tech Stack
This project leverages the following tools and libraries:

1. Python – Core programming language
2. Pandas – Data manipulation and analysis
3. NumPy – Numerical operations
4. Scikit-learn – ML models, preprocessing, and evaluation
5. XGBoost – Advanced gradient boosting classifier
6. Jupyter Notebook – Interactive development and experimentation
7. NLP Techniques –
     * TF-IDF (Term Frequency-Inverse Document Frequency)
     * Regular Expressions (Regex)
     * Tokenization

