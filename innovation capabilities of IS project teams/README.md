
# Innovation Capabilities of IS Project Teams

This repository contains the project file **Innovation Capabilities of IS Project Teams.qmd**, which analyzes the innovation capabilities of IS project teams based on a structured questionnaire. The analysis includes both descriptive and inferential statistical methods, supported by visualizations and regression modeling.

---

## Project Overview

### Objective:
The primary goal of this project is to explore factors influencing innovation capabilities in IS project teams. Using quantitative methods, the data collected from a questionnaire has been analyzed to uncover patterns and relationships.

### Data:
- **Source**: Questionnaire with six dimensions of IT project paradoxes:
  1. Work atmosphere during the project
  2. Socialisation and collaboration
  3. Project coordination
  4. Knowledge sharing and management
  5. Project performance
  6. Project characteristics
- **Format**: CSV file with:
  - **12 numerical variables**
  - **3 categorical variables**

---

## Methodology

The analysis follows these steps:

1. **Data Loading and Preprocessing**:
   - Imported the dataset (`PARA5.csv`) and prepared it for analysis.
   - Addressed missing values and ensured data consistency.

2. **Descriptive Analysis**:
   - Measures such as mean, variance, and distribution were computed.
   - Visualizations were created to explore the spread and tendency of data.

3. **Inferential Analysis**:
   - **ANOVA Tests**: Conducted to examine significant group differences.
   - **Linear Regression Modeling**: Explored relationships between numerical variables.

4. **Visualization**:
   - Static plots (e.g., histograms, box plots) using **ggplot2**.
   - Interactive plots with **plotly** for deeper insights.

5. **Results**:
   - Identified significant patterns and relationships.
   - Regression equations provided quantitative insights into innovation factors.

---

## Key Outputs

1. **HTML Report**:
   - A self-contained report summarizing the entire analysis.
2. **Visualizations**:
   - Graphs and plots to illustrate trends and relationships in the data.
3. **Key Findings**:
   - Insightful summaries of statistical analysis and regression results.

---

## Visualizations

### 1. **Data Distribution Visualization**

**Description:**  
This section visualizes the distribution of key numerical variables. The histogram below illustrates the distribution of **Project Performance**, showing the spread and central tendency of responses.

![Histogram of Project Performance](images/project_performance_histogram.png)

---

### 2. **Correlation Matrix**

**Description:**  
To understand the relationships between numerical variables, a correlation matrix was created. The heatmap below highlights the strength and direction of relationships between variables.

![Correlation Matrix](images/correlation_matrix.png)

---

### 3. **ANOVA Results Visualization**

**Description:**  
This visualization shows the results of the ANOVA tests. The box plot below highlights variations in **Project Performance** across different **Project Characteristics** categories.

![Box Plot for ANOVA Results](images/anova_boxplot.png)

---

### 4. **Linear Regression Analysis**

**Description:**  
The scatter plot below, along with the regression line, demonstrates the relationship between **Project Coordination** and **Project Performance**, providing insights into the strength and direction of the association.

![Linear Regression Plot](images/linear_regression_plot.png)

---

## Repository Structure

- **`Innovation Capabilities of IS Project Teams.qmd`**: The main Quarto Markdown file containing the analysis code and documentation.
- **`report.html`**: The final self-contained HTML report.
- **`PARA5.csv`**: The dataset used for analysis.
- **`images/`**: Folder containing all visualizations.
- **`README.md`**: This documentation file.

---

## How to View the Results

1. Clone this repository:
   ```bash
   git clone https://github.com/USERNAME/REPOSITORY_NAME.git
   ```
2. Open the `report.html` file in any browser to view the analysis and results.

---

## Required Packages

### Data Processing:
- `readr`, `dplyr`, `tidyr`

### Visualization:
- `ggplot2`, `plotly`

### Statistical Analysis:
- `lmtest`, `car`, `psych`

### Rendering:
- `quarto`, `rmarkdown`, `knitr`

Install these packages in R:
```r
install.packages(c("readr", "dplyr", "tidyr", "ggplot2", "plotly", "lmtest", "car", "psych", "quarto", "rmarkdown", "knitr"))
```

---

## How to Reproduce

1. Open the `Innovation Capabilities of IS Project Teams.qmd` file in RStudio or a Quarto-supported editor.
2. Render the file:
   ```bash
   quarto render "Innovation Capabilities of IS Project Teams.qmd"
   ```

---
