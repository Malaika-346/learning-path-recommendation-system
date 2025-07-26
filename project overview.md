# 🚀 Learning Path Recommendation System

A personalised learning recommendation system for interns that suggests relevant course modules using collaborative filtering.

---

## 📌 Project Overview

This system analyses past learning patterns of interns along with course metadata to recommend tailored learning paths. The goal is to enhance intern performance by suggesting the most relevant modules based on their interests and previous activity.

---

## 🧠 Features

- 📚 Uses collaborative filtering via matrix factorization (SVD)
- 📊 Incorporates course metadata (difficulty, category)
- 🎯 Recommends courses based on simulated intern feedback
- ✅ Fully implemented in a **single cell** notebook for clean professional use
- 🧾 Error-free and fast runtime on Kaggle

---

## 🛠️ Tools & Libraries

- Python 3
- NumPy, Pandas
- scikit-learn
- Kaggle Notebook environment

---

## 📈 Model Used

- **Collaborative Filtering** (Matrix Factorization via `TruncatedSVD`)
- Intern-course rating matrix → Dimensionality reduction → Predictions

---

## 📁 Files in Repository

| File                          | Description                                |
|------------------------------|--------------------------------------------|
| `learning-path-system.ipynb` | Main notebook with complete working code   |
| `README.md`                  | Project overview and usage guide           |

---

## 🧪 How to Run (Kaggle Notebook)

1. Go to [Kaggle](https://www.kaggle.com/code)
2. Click “New Notebook”
3. Upload the file `learning-path-system.ipynb`
4. Run all cells (it's all in **one cell**)
5. View the printed recommendations for each intern

---

## 📸 Sample Output

> ✅ Intern_1 is recommended:
> - *Deep Learning with TensorFlow* (Score: 4.9)  
> - *Data Visualisation in Python* (Score: 4.7)

> ✅ Intern_2 is recommended:
> - *Machine Learning Basics*  
> - *SQL for Data Analysis*

*(Based on predicted relevance and metadata)*

---

