# 📊 Academic Performance Modeling

Statistical Analysis and Predictive Modeling of Student Achievement

# 🚀 Project Summary

This project investigates the determinants of academic performance among secondary school students using demographic, social, and behavioral data.

The objective is to identify key predictors of student achievement and evaluate statistical models capable of explaining variation in final grades.

The analysis follows a fully reproducible data science workflow including data preparation, exploratory analysis, statistical modeling, and diagnostic evaluation.

# 🎯 Key Questions

- Which factors are most strongly associated with academic performance?

- How well can student outcomes be predicted using observed characteristics?

- What behavioral or socioeconomic variables show the greatest explanatory power?

- Do statistical assumptions hold for modeling educational performance?

# 🧠 Analytical Approach

The project follows a structured modeling pipeline:

<pre>
Data ingestion
   ↓
Data cleaning and harmonization
   ↓
Exploratory data analysis
   ↓
Statistical modeling
   ↓
Model diagnostics and validation
   ↓
Interpretation and reporting
</pre>

# 📂 Data Description

Two datasets describing student performance were analyzed:

- Mathematics course performance.

- Portuguese language course performance.

Each dataset includes:

- Demographics

- Family background

- Study habits

- School-related variables

- Academic outcomes (final grades)

Raw data is preserved unchanged for reproducibility.

# 🔬 Methodology
## Data Preparation

- Reproducible data loading using project-root paths

- Dataset merging and consistency checks

- Variable inspection and cleaning

## Exploratory Data Analysis

- Distributional analysis

- Bivariate relationships

- Outlier detection

- Assumption testing

## Statistical Modeling

- Regression-based modeling of academic performance

- Evaluation of predictor significance

- Diagnostic tests for model validity

## Model Diagnostics

- Residual analysis

- Distributional checks

- Fit assessment

# 📈 Key Analytical Outputs

The project generates:

- Distribution plots

- Relationship visualizations

- Diagnostic plots

- Statistical summaries

- Final analytical report

All outputs are automatically saved for reproducibility.

# 📊 Example Visualizations

Figures produced during the analysis include:

- Variable distributions

- Predictor–outcome relationships

- Residual diagnostics

- Model assumption checks

Saved in:
<pre>
outputs/figures/
</pre>

# 🧱 Project Structure

<pre>
academic-performance-modeling/
│
├── data/
│   ├── raw/           # Original datasets (immutable)
│   └── processed/     # Cleaned datasets
│
├── outputs/
│   ├── figures/       # Visualizations
│   ├── models/        # Saved model objects
│   └── tables/        # Statistical outputs
│
├── reports/
│   ├── R Markdown analysis
│   └── Rendered HTML report
│
├── scripts/           # Modular analysis scripts
│
└── project file
</pre>

# 🔁 Reproducibility

This project is fully reproducible.

All file paths are managed relative to the project root, ensuring portability across environments.

To reproduce the analysis

1. Clone the repository

2. Open the project file in RStudio

3. Install required packages:

<pre>
install.packages(c("tidyverse", "here", "knitr"))
</pre>

4. Render the report located in:

<pre>
reports/
</pre>

# 🛠 Tools and Techniques

- R
- R Markdown
- Reproducible research workflow
- Statistical modeling
- Data visualization
- Diagnostic testing

# 🎓 Analytical Value

This project demonstrates the application of statistical modeling to real-world educational data, including:

- structured analytical design
- model-based inference
- reproducible workflows
- interpretable results

It reflects practical competencies required in applied data science and quantitative research.

# 📌 Potential Extensions

Future improvements may include:

- Machine learning models for prediction comparison
- Cross-validation frameworks
- Feature importance analysis
- Model performance benchmarking
- Causal inference approaches

# 👤 Author

Brayan Alexander Salgado Blanco
MSc Data Science Student
Economist