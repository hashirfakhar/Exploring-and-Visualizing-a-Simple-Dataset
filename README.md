# Task 1 – Exploring and Visualizing a Simple Dataset

## Objective
The goal of this task is to explore and visualize the famous Iris dataset using Python libraries such as pandas, seaborn, and matplotlib. This exercise helps develop basic data exploration and visualization skills, which are essential for any data scientist.

## Approach
- Loaded the Iris dataset using Seaborn
- Inspected dataset structure with `.shape`, `.columns`, and `.head()`
- Checked for missing values and duplicates
- Performed Exploratory Data Analysis (EDA), including:
  - Histograms for feature distributions
  - Box plots for outlier detection
  - Scatter plots to analyze relationships between features
  - Correlation heatmap to observe relationships between numeric variables

## Results and Insights
- The dataset contains 150 rows and 5 columns (4 features + 1 target).
- No missing values or duplicates were found.
- Petal measurements (length & width) show strong separation among the three species.
- Setosa species is easily distinguishable based on petal features.
- High positive correlation observed between `petal_length` and `petal_width` (~0.96).
- Visualization confirms that petal features are better discriminators of species than sepal features.

---
This task served as a foundation for future classification tasks and model building by understanding data patterns visually.
