![Anime Project](Power%20Point/image.png)

# 📊 Anime Data Science Project

A complete project of **Exploratory Data Analysis (EDA)** and **Machine Learning** applied to an anime dataset, including advanced statistical analyses such as ANOVA, linear regression, and clustering.

---

## 📋 Project Description

This project performs a comprehensive analysis of anime data from **MyAnimeList**. The objective is to explore patterns, relationships, and characteristics of anime series using statistical analysis techniques and unsupervised machine learning.

### Academic Context
Project completed as part of **Data Science** training that integrates:
- Exploratory Data Analysis (EDA)
- Statistical Tests (ANOVA)
- Linear Regression
- Unsupervised Clustering
- Data Visualization

---

## 🗂️ Project Structure

```
Anime-Data-Science-Project/
├── README.md                          # This file
├── LICENSE                            # Project MIT License
├── requirements.txt                   # Project Dependencies
├── Jupyter Notebook/
│   ├── data.csv                       # Main anime dataset
│   ├── notebook.ipynb                 # EDA: Exploratory Analysis
│   ├── anova.ipynb                    # ANOVA Analysis
│   ├── regresionlineal.ipynb          # Linear Regression
│   └── clustering.ipynb               # Clustering Analysis
└── Power Point/                       # Project Presentations
```

---

## 📁 Notebooks Description

### 1. **notebook.ipynb** - Exploratory Data Analysis (EDA)
**Purpose:** Initial exploration and understanding of the dataset

**Content:**
- Loading and reviewing dataset structure
- Descriptive statistics of quantitative variables
- Distribution of variables (Episodes, Duration, Score, etc.)
- Identification of outliers
- Correlation analysis
- Exploratory visualizations

**Variables analyzed:**
- Episodes (Number of episodes)
- Duration_Minutes (Duration in minutes)
- Score (Average score)
- Scored_Users (Users who rated)
- Ranked (Ranking)
- Popularity (Popularity index)
- Members (Number of members)

**Tools:** `pandas`, `numpy`, `matplotlib`, `seaborn`

---

### 2. **anova.ipynb** - Analysis of Variance (ANOVA)
**Purpose:** Determine if there are statistically significant differences in scores between anime types

**Research Question:**
Are there statistically significant differences in Score between different anime types (TV, Movie, OVA, ONA, Special, etc.)?

**Content:**
- Descriptive statistics by anime type
- Normality tests (Shapiro-Wilk)
- Homogeneity of variance tests (Levene)
- Parametric ANOVA (if assumptions are met)
- Non-parametric tests (Kruskal-Wallis)
- Post-hoc analysis (pairwise comparisons)
- Visualizations (boxplots, violinplots)

**Hypothesis:**
- **H₀:** No differences in mean score between anime types
- **H₁:** There are significant differences

**Tools:** `scipy.stats`, `matplotlib`, `seaborn`

---

### 3. **regresionlineal.ipynb** - Linear Regression Analysis
**Purpose:** Model the relationship between variables and predict scores

**Content:**
- Selection of predictive variables
- Construction of linear regression model
- Evaluation of regression assumptions
- Interpretation of coefficients
- Goodness of fit metrics (R², RMSE, MAE)
- Residual analysis
- Predictions

**Tools:** `scikit-learn`, `scipy`, `matplotlib`

---

### 4. **clustering.ipynb** - K-Means Clustering Analysis
**Purpose:** Identify groups or natural patterns in anime data

**Methodology:**
1. **Preprocessing:** Data cleaning and feature selection
2. **Normalization:** Data scaling (StandardScaler)
3. **K Selection:** Elbow Method
4. **Clustering:** Application of K-Means algorithm
5. **Visualization:** PCA for reduction to 2D
6. **Interpretation:** Centroid analysis

**Features used:**
- Episodes
- Duration
- Score
- Popularity
- Members

**Identifiable Clusters:**
- Mainstream hits
- Niche series
- Movies
- Long-running programs

**Tools:** `scikit-learn`, `matplotlib`, `seaborn`

---

## 📊 Dataset (data.csv)

**Source:** MyAnimeList

**Main Features:**
- Type (Anime type: TV, Movie, OVA, ONA, Special, etc.)
- Episodes (Number of episodes)
- Duration_Minutes (Duration)
- Score (User score)
- Scored_Users (Number of users who rated)
- Ranked (Ranking)
- Popularity (Popularity index)
- Members (Number of members)

---

## 🛠️ Installation and Configuration

### Prerequisites
- Python 3.7 or higher
- pip or conda

### Installing Dependencies

```bash
pip install -r requirements.txt
```

### Main Dependencies
```
pandas          # Data manipulation
matplotlib      # Visualization
seaborn         # Statistical visualization
scikit-learn    # Machine Learning
ipykernel       # Jupyter Kernel
numpy           # Numerical computation
scipy           # Statistical analysis
```

---

## 🚀 How to Run

### Option 1: Jupyter Notebook
```bash
jupyter notebook
```
Then open any `.ipynb` files in the `Jupyter Notebook/` folder

### Option 2: JupyterLab
```bash
jupyter lab
```

---

## 📈 Results and Conclusions

This project provides insights about:

1. **Anime Dataset Characteristics**
   - Distribution of scores
   - Relationship between number of episodes and score
   - Popularity trends

2. **Differences by Anime Type**
   - ANOVA reveals if there are significant differences
   - Comparisons between TV, Movies, OVAs, etc.

3. **Score Prediction**
   - Linear regression identifies influencing factors
   - Model to estimate scores

4. **Anime Segmentation**
   - Clustering groups anime into interpretable categories
   - Identification of niches and trends

---

## 👨‍💻 Author

**Darian** - Data Science School Project

---

## 📝 License

This project is under the **MIT License (Massachusetts Institute of Technology)**.
**Full details in:** [LICENSE](LICENSE)


---