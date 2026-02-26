# 🧰 DSInterviewKit

> **Your one-stop open-source kit for cracking Data Science interviews.**  
> Curated resources, practice questions, cheat sheets, and guides — from fundamentals to advanced topics.

![GitHub stars](https://img.shields.io/github/stars/yourusername/DSInterviewKit?style=social)
![Contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen)
![License](https://img.shields.io/badge/license-MIT-blue)
![Maintained](https://img.shields.io/badge/maintained-yes-success)

---

## 👥 Who Is This For?

This repository is targeted at students and professionals from:

| Background | How this helps |
|---|---|
| 🖥️ Computer Science | ML, system design, coding, architecture |
| 📐 Mathematics | Statistics, probability, linear algebra |
| 📊 Statistics | Distributions, hypothesis testing, inference |
| ⚙️ Engineering | Applied ML, data pipelines, optimization |

Whether you're a **fresh graduate** or an **experienced professional**, this repo covers everything from beginner fundamentals to advanced interview-level questions.

---

## 📌 Table of Contents

- [📊 Statistics & Probability](#-statistics--probability)
- [🖥️ Computer Architecture](#️-computer-architecture)
- [🤖 Machine Learning](#-machine-learning)
- [🐍 Python & Pandas](#-python--pandas)
- [🗄️ SQL](#️-sql)
- [📐 Linear Algebra & Calculus](#-linear-algebra--calculus)
- [🧩 Case Studies](#-case-studies)
- [🎯 Behavioral & HR Questions](#-behavioral--hr-questions)
- [🗺️ Study Roadmap](#️-study-roadmap)
- [📚 Resources & Books](#-resources--books)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)

---

## 📊 Statistics & Probability

Core area for almost every data science interview. Covers:

- Descriptive statistics — mean, median, mode, variance, standard deviation
- Probability basics — sample space, events, rules of probability
- **Mutually exclusive events** — P(A ∩ B) = 0
- **Exhaustive events** — P(A ∪ B) = 1
- **Independent events** — P(A ∩ B) = P(A) × P(B)
- Probability distributions — Normal, Binomial, Poisson, Uniform
- Bayes' Theorem and conditional probability
- Hypothesis testing — null/alternative hypothesis, p-value, Type I & II errors
- Confidence intervals and significance levels
- Central Limit Theorem
- Correlation vs Causation

📁 Folder: `statistics-probability/`

---

## 🖥️ Computer Architecture

Often overlooked but tested at top tech companies. Covers:

- CPU vs GPU — why GPUs matter for ML
- Memory hierarchy — cache, RAM, disk and their impact on performance
- Parallel computing and vectorization
- Data storage formats — CSV, Parquet, HDF5, JSON
- Big data concepts — distributed computing, MapReduce basics
- Cloud computing fundamentals — storage, compute, scalability
- Latency vs throughput tradeoffs

📁 Folder: `computer-architecture/`

---

## 🤖 Machine Learning

The core of most data science interviews. Covers:

- Supervised vs Unsupervised vs Reinforcement Learning
- Linear & Logistic Regression
- Decision Trees, Random Forests, Gradient Boosting (XGBoost, LightGBM)
- Support Vector Machines
- Neural Networks & Deep Learning basics
- Clustering — K-Means, DBSCAN, Hierarchical
- Dimensionality reduction — PCA, t-SNE
- Model evaluation — accuracy, precision, recall, F1, ROC-AUC
- Overfitting & underfitting — regularization (L1, L2), dropout
- Cross-validation strategies
- Feature engineering & selection
- Natural Language Processing basics

📁 Folder: `machine-learning/`

---

## 🐍 Python & Pandas

Practical coding skills tested in interviews. Covers:

- Python fundamentals — lists, dicts, comprehensions, OOP
- NumPy — array operations, broadcasting, vectorization
- Pandas — DataFrames, groupby, merge, pivot, apply
- Data cleaning — handling nulls, duplicates, outliers
- Common interview coding patterns
- Matplotlib & Seaborn for visualization
- Scikit-learn pipeline basics

📁 Folder: `python-pandas/`

---

## 🗄️ SQL

SQL is tested in almost every data role. Covers:

- SELECT, WHERE, GROUP BY, HAVING, ORDER BY
- JOINs — INNER, LEFT, RIGHT, FULL OUTER, SELF
- Window functions — ROW_NUMBER, RANK, LAG, LEAD
- Subqueries and CTEs
- Aggregations and date functions
- Query optimization and indexing
- Real-world SQL interview problems

📁 Folder: `sql/`

---

## 📐 Linear Algebra & Calculus

Essential mathematical foundations. Covers:

- Vectors and matrices — operations, transpose, inverse
- Eigenvalues and eigenvectors
- Matrix decomposition — SVD, LU
- Dot products and projections
- Gradients and partial derivatives
- Chain rule and backpropagation
- Optimization — gradient descent, learning rate, convergence

📁 Folder: `linear-algebra-calculus/`

---

## 🧩 Case Studies

Real-world problems to practice end-to-end thinking. Covers:

- A/B testing design and analysis
- Business metric definition and tracking
- Anomaly detection scenarios
- Recommendation system design
- Churn prediction problems
- Data leakage identification
- "How would you build X?" open-ended questions

📁 Folder: `case-studies/`

---

## 🎯 Behavioral & HR Questions

Often underestimated but critical for clearing final rounds. Covers:

- Tell me about yourself / your projects
- Explain a complex model to a non-technical stakeholder
- Handling disagreements with team members
- When a model failed — what did you do?
- Why data science? Why this company?
- STAR method — Situation, Task, Action, Result

📁 Folder: `behavioral/`

---

## 🗺️ Study Roadmap

Follow this topic-by-topic progression for structured preparation:

| Stage | Focus Area | Why It Matters |
|---|---|---|
| 🔵 Foundation | Statistics & Probability | Base for all ML and data reasoning |
| 🔵 Foundation | Linear Algebra & Calculus | Math behind ML algorithms |
| 🟡 Core | Machine Learning | Heart of every data science interview |
| 🟡 Core | Python, NumPy & Pandas | Practical coding and data manipulation |
| 🟡 Core | SQL | Tested in almost every data role |
| 🟠 Applied | Computer Architecture | System design and performance thinking |
| 🟠 Applied | Case Studies | End-to-end real-world problem solving |
| 🔴 Final | Behavioral & HR Questions | Critical for clearing final rounds |

> 💡 **Tip:** Don't skip the Foundation stage. Strong fundamentals in stats and math separate good candidates from great ones.

---

## 📚 Resources & Books

**Books**
- *The Elements of Statistical Learning* — Hastie, Tibshirani, Friedman
- *Hands-On Machine Learning* — Aurélien Géron
- *Python for Data Analysis* — Wes McKinney
- *Naked Statistics* — Charles Wheelan (great for stats intuition)

**Online Platforms**
- [LeetCode](https://leetcode.com) — SQL & Python coding
- [StrataScratch](https://stratascratch.com) — real DS interview questions
- [Kaggle](https://kaggle.com) — datasets and notebooks
- [StatQuest (YouTube)](https://www.youtube.com/@statquest) — statistics & ML visuals

**Cheat Sheets**
- Pandas cheat sheet — `resources/pandas-cheatsheet.pdf`
- SQL cheat sheet — `resources/sql-cheatsheet.pdf`
- ML algorithms summary — `resources/ml-algorithms.pdf`
- Probability formulas — `resources/probability-formulas.pdf`

---

## 🤝 Contributing

Contributions are welcome and appreciated! Here's how:

1. Fork the repository
2. Create a new branch: `git checkout -b feature/your-topic`
3. Add your content (questions, explanations, resources)
4. Commit your changes: `git commit -m "Add: topic name"`
5. Push and open a Pull Request

Please follow the existing folder structure and keep explanations clear and beginner-friendly.

---

## 🌟 Show Your Support

If this repo helped you, please consider giving it a ⭐ — it helps others find it too!

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙋 Connect

Made with ❤️ for the data science community.  
Feel free to connect on [LinkedIn](https://linkedin.com) | [Twitter/X](https://twitter.com)

---

*"The goal is to turn data into information, and information into insight."* — Carly Fiorina
