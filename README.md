# Student Performance Data Science Mini Project

## Project Overview

This mini-project performs exploratory data analysis (EDA) on a student-performance dataset. The objective is to identify meaningful patterns and relationships between academic performance and factors such as weekly self-study hours, attendance, and class participation.

## Dataset

The project uses `student_performance.csv`.

The dataset contains student-level records with these fields:

| Column | Description |
|---|---|
| `student_id` | Student identifier |
| `weekly_self_study_hours` | Weekly self-study hours |
| `attendance_percentage` | Attendance percentage |
| `class_participation` | Class participation measure |
| `total_score` | Total academic score |
| `grade` | Student grade category |

## Questions Explored

- How are total scores distributed?
- Which grades are most common?
- Is self-study time associated with total score?
- Is attendance associated with total score?
- Is class participation associated with total score?
- Which numerical variables have the strongest relationship with total score?

## Analysis Performed

The notebook includes:

1. Data loading
2. Dataset inspection
3. Data-quality checks
4. Descriptive statistics
5. Total-score distribution
6. Grade distribution
7. Self-study-hours vs total-score analysis
8. Attendance vs total-score analysis
9. Class-participation vs total-score analysis
10. Correlation heatmap
11. Grouped performance summaries
12. Identification of the strongest correlations
13. Final conclusions and future scope

## Visualizations

The project uses:

- Histograms
- Bar charts
- Scatter plots
- Regression trend lines
- Correlation heatmap

## Key Findings

The notebook calculates the numerical evidence needed to identify the strongest relationships in the dataset. Because the analysis is intended to be reproducible, the README does not hard-code results that could become inconsistent with a changed dataset.

After running the notebook, the `correlations_with_score` output provides the ranking of numerical relationships with `total_score`.

## Important Note

Correlation represents association and does not establish causation. For example, a positive relationship between attendance and score would not by itself prove that increasing attendance causes a specific increase in scores.

## Future Scope

A natural next step is to build a machine-learning model that predicts `total_score` using the available student characteristics. This can extend the project from descriptive analytics into predictive analytics.

## Repository Structure

```text
student-performance-data-science/
├── Student_Performance_Analysis.ipynb
├── student_performance.csv
├── requirements.txt
└── README.md
```

## How to Run

### Google Colab

1. Upload the repository files to GitHub.
2. Open `Student_Performance_Analysis.ipynb` in Google Colab.
3. Ensure `student_performance.csv` is available in the Colab working directory.
4. Run all cells.

### Local Jupyter

Install the dependencies:

```bash
pip install -r requirements.txt
```

Then open the notebook:

```bash
jupyter notebook Student_Performance_Analysis.ipynb
```

## Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Project Type

**Data Science Mini Project — Exploratory Data Analysis**


