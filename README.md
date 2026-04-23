# Student-Habits-vs-Academic-Performance-
# 📚 Student Habits vs Academic Performance

## Overview

This project explores the relationship between **student habits** and their **academic performance**. By analyzing behavioral patterns — such as study routines, sleep schedules, social media usage, physical activity, and attendance — we aim to uncover meaningful correlations and predictive insights that can help students, educators, and institutions improve learning outcomes.

---

## 🎯 Objectives

- Identify which daily habits have the strongest positive or negative impact on academic performance.
- Visualize patterns between lifestyle choices and GPA/test scores.
- Build predictive models to estimate academic outcomes based on student behavior data.
- Provide actionable recommendations for students and educators.

---

## 📂 Dataset Description

The dataset captures a variety of student habit variables alongside academic metrics:

| Feature | Description |
|---|---|
| `study_hours_per_day` | Average hours spent studying daily |
| `sleep_hours_per_night` | Average hours of sleep per night |
| `social_media_hours` | Daily hours spent on social media |
| `attendance_rate` | Percentage of classes attended |
| `extracurricular_activities` | Number of activities participated in |
| `exercise_frequency` | Days per week of physical activity |
| `part_time_job` | Whether the student holds a part-time job (Yes/No) |
| `mental_health_rating` | Self-reported mental wellness score (1–10) |
| `GPA` | Cumulative Grade Point Average (target variable) |
| `exam_score` | Final exam score (%) |

---

## 🔍 Key Research Questions

1. Do students who sleep more perform better academically?
2. Is there a negative correlation between social media usage and GPA?
3. How does study time relate to exam scores?
4. Does physical activity positively influence academic outcomes?
5. What combination of habits best predicts high academic performance?

---

## 🛠️ Technologies Used

- **Python** — Data processing and modeling
- **Pandas / NumPy** — Data manipulation
- **Matplotlib / Seaborn** — Data visualization
- **Scikit-learn** — Machine learning models
- **Jupyter Notebook** — Exploratory analysis

---

## 📊 Analysis Workflow

```
1. Data Collection & Cleaning
        ↓
2. Exploratory Data Analysis (EDA)
        ↓
3. Correlation & Statistical Analysis
        ↓
4. Feature Engineering
        ↓
5. Predictive Modeling (Regression / Classification)
        ↓
6. Insights & Recommendations
```

---

## 📈 Key Findings *(Summary)*

- **Study hours** show the strongest positive correlation with GPA.
- **Sleep quality** significantly affects concentration and retention.
- **Excessive social media** usage (4+ hours/day) is linked to lower exam scores.
- Students with **regular exercise** report better mental health and higher focus levels.
- **Attendance rate** is a reliable predictor of academic success.

---

## 🚀 Getting Started

### Prerequisites

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### Run the Analysis

```bash
# Clone the repository
git clone https://github.com/your-username/student-habits-performance.git

# Navigate to the project directory
cd student-habits-performance

# Launch Jupyter Notebook
jupyter notebook
```

---

## 📁 Project Structure

```
student-habits-performance/
│

│
├── notebooks/
│   ├── 01_eda.ipynb          # Exploratory Data Analysis
│   ├── 02_visualization.ipynb
│   └── 03_modeling.ipynb     # Predictive models
│
├── src/
│   ├── preprocess.py
│   ├── visualize.py
│   └── model.py
│
├── results/
│   └── figures/              # Generated plots and charts
│
├── README.md
└── requirements.txt
```

---

## 🤝 Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements, bug fixes, or additional analyses.

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

## 👥 Authors

- **Your Name** — *Initial work* — [GitHub Profile](https://github.com/your-username)

---

> *"Success is the sum of small efforts, repeated day in and day out."* — Robert Collier
