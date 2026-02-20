# 📊 Academic Performance Modeling

Statistical Analysis and Predictive Modeling of Student Achievement

# 🚀 Project Summary

This project investigates the determinants of academic performance among secondary school students using demographic, social, and behavioral data.

The objective is to identify key predictors of student achievement and evaluate statistical models capable of explaining variation in final grades.

The analysis follows a fully reproducible data science workflow including data preparation, exploratory analysis, statistical modeling, and diagnostic evaluation.

# 🌐 Full Interactive Report

Explore the complete analysis, interactive visualizations, and detailed statistical results:

👉 <https://brysb.github.io/academic-performance-modeling/>

# 🎯 Key Questions

-   Which factors are most strongly associated with academic performance?

-   How well can student outcomes be predicted using observed characteristics?

-   What behavioral or socioeconomic variables show the greatest explanatory power?

-   Do statistical assumptions hold for modeling educational performance?

# 🧠 Analytical Approach

The project follows a structured modeling pipeline:

```{=html}
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
```

# 📂 Data Description

Two datasets describing student performance were analyzed:

-   Mathematics course performance.

-   Portuguese language course performance.

Each dataset includes:

-   Demographics

-   Family background

-   Study habits

-   School-related variables

-   Academic outcomes (final grades)

Raw data is preserved unchanged for reproducibility.

# 🔬 Methodology

## Data Preparation

-   Reproducible data loading using project-root paths

-   Dataset merging and consistency checks

-   Variable inspection and cleaning

## Exploratory Data Analysis

-   Distributional analysis

-   Bivariate relationships

-   Outlier detection

-   Assumption testing

## Statistical Modeling

-   Regression-based modeling of academic performance

-   Evaluation of predictor significance

-   Diagnostic tests for model validity

## Model Diagnostics

-   Residual analysis

-   Distributional checks

-   Fit assessment

# 📈 Key Analytical Outputs

The project generates:

-   Distribution plots

-   Relationship visualizations

-   Diagnostic plots

-   Statistical summaries

-   Final analytical report

All outputs are automatically saved for reproducibility.

# 📌 Key Findings

* A comparative modeling approach was used to evaluate the predictive performance of different functional specifications for final student grades.

* Two model forms were tested:

  - a standard linear specification (Lin–Lin).

  - a log–log specification designed to address potential nonlinearity, skewness, and heteroscedasticity.

* Model selection criteria strongly favored the log–log specification, which achieved substantially lower information criteria values:


| Model   | AIC     | BIC     |
| ------- | ------- | ------- |
| Lin–Lin | 1653.66 | 1665.60 |
| Log–Log | 594.39  | 606.33  |


* The large reduction in both AIC and BIC indicates that the log–log model provides a significantly better balance between goodness of fit and model parsimony.

* Logarithmic transformation of both predictors and outcome improved variance stability, enhanced linearity, and reduced the influence of extreme values, resulting in more reliable and robust predictions of final academic performance.

Overall, model comparison demonstrates that functional form specification plays a critical role in predictive accuracy, and that log-transformed models offer a superior framework for explaining variation in student achievement.

# 📊 Example Visualizations

* Relationship Between Partial and Final Grades (Mathematics)

![Relationship Between Partial and Final Grades (Mathematics)](C:/Users/basbo/Documents/GitHub/academic-performance-modeling/outputs/figuresfig-dispersion-1.png)

This plot shows the strong linear relationship between intermediate assessments and final performance, supporting their predictive value in the modeling framework.

* Distribution of Final Grades by Subject

![Distribution of Final Grades by Subject](C:/Users/basbo/Documents/GitHub/academic-performance-modeling/outputs/figuresfig-boxplot-1.png)

The distribution of final grades varies across subjects, revealing differences in central tendency and dispersion that are important for model specification and interpretation.


Figures produced during the analysis include:

-   Variable distributions
-   Predictor–outcome relationships
-   Residual diagnostics
-   Model assumption checks

Saved in:

```{=html}
<pre>
outputs/figures/
</pre>
```

# 🧠 Analytical Interpretation

Academic performance is influenced by structured relationships between intermediate assessments and final outcomes, as well as differences in grade distributions across subjects.

The modeling results show that selecting an appropriate functional form is critical for capturing these relationships accurately. The log–log specification provides a more stable and statistically robust representation of the data-generating process.

# 🧱 Project Structure

```{=html}
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
```

# 🔁 Reproducibility

This project is fully reproducible.

All file paths are managed relative to the project root, ensuring portability across environments.

To reproduce the analysis

1.  Clone the repository

2.  Open the project file in RStudio

3.  Install required packages:

```{=html}
<pre>
install.packages(c("tidyverse", "here", "knitr"))
</pre>
```

4.  Render the report located in:

```{=html}
<pre>
reports/
</pre>
```

# 🛠 Tools and Techniques

-   R
-   R Markdown
-   Reproducible research workflow
-   Statistical modeling
-   Data visualization
-   Diagnostic testing

# 🎓 Analytical Value

This project demonstrates the application of statistical modeling to real-world educational data, including:

-   structured analytical design
-   model-based inference
-   reproducible workflows
-   interpretable results

It reflects practical competencies required in applied data science and quantitative research.

# 📌 Potential Extensions

Future improvements may include:

-   Machine learning models for prediction comparison
-   Cross-validation frameworks
-   Feature importance analysis
-   Model performance benchmarking
-   Causal inference approaches

# 👤 Author

Brayan Alexander Salgado Blanco MSc Data Science Student Economist
