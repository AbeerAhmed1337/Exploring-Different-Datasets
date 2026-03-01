# Task 1: Exploring and Visualizing a Simple Dataset
### DevelopersHub AI/ML Engineering Internship

---

## Overview

The goal of this task was to get hands-on with the fundamentals of data exploration — loading a real dataset, inspecting its structure, and using visualizations to surface patterns that aren't obvious from raw numbers alone. The Iris dataset was a natural starting point: small enough to be manageable, but rich enough to actually be interesting.

---

## Dataset

| Property | Details |
|----------|---------|
| Name | Iris Dataset |
| Source | Loaded directly from URL via pandas |
| Samples | 150 (50 per species) |
| Features | 4 numerical (sepal length, sepal width, petal length, petal width) |
| Target | 1 categorical (species: Setosa, Versicolor, Virginica) |

No local download required — the dataset is fetched directly in the notebook.

---

## Project Structure

```
task-1-iris-visualization/
├── iris_exploration.ipynb   # Main notebook with all analysis and plots
├── requirements.txt         # Dependencies
└── README.md
```

---

## Setup & Usage

**1. Clone the repository**
```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
cd YOUR_REPO_NAME
```

**2. Install dependencies**
```bash
pip install -r requirements.txt
```

**3. Run the notebook**
```bash
jupyter notebook iris_exploration.ipynb
```

---

## Dependencies

```
pandas
matplotlib
seaborn
jupyter
```

---

## Key Findings

- **Clean data** — no missing values, perfectly balanced classes across all three species.
- **Setosa stands apart** — even a basic scatter plot reveals that Setosa forms a tight, isolated cluster, while Versicolor and Virginica overlap more with each other.
- **Petal measurements are more informative** — petal length and petal width showed far clearer species separation than sepal measurements.
- **Minor outliers in sepal width** — a few data points fall outside the typical range, though nothing that suggests data quality issues.

---

## Visualizations

The following plot types were used to explore the data from different angles:

- **Scatter plots** — to examine relationships between features and spot species clustering
- **Histograms** — to understand the distribution of each individual feature
- **Box plots** — to compare feature ranges across species and identify outliers

---

## What I Learned

Working through this task reinforced how much you can learn about a dataset before any modeling happens. Choosing the right visualization for the right question matters — a histogram and a scatter plot on the same data tell completely different stories. It also highlighted how some features (like petal dimensions) carry far more signal than others, which has direct implications for feature selection in later tasks.

---

## Author

**[Your Name]**
DevelopersHub AI/ML Engineering Internship
