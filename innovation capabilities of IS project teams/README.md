
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
This section visualizes the Descriptive Statistics such as bar charts ,  histograms of distribution, density plot, boxplot, of key numerical variables, and also descrpitive statistics of categorical columns as below:


![image](https://github.com/user-attachments/assets/1a434465-60ff-4290-9b1c-a99db29b5d87)

![image](https://github.com/user-attachments/assets/0348f3e8-b4f1-4be1-be16-8fcf1a87b58e)

![image](https://github.com/user-attachments/assets/8ced7209-dbe0-42b7-a8ac-06a36c75ce47)

![image](https://github.com/user-attachments/assets/bd36b2bc-0b00-4a75-9957-58eb0c56b245)

![image](https://github.com/user-attachments/assets/1264adb3-7721-44d7-8e0e-cac2128c9cfc)

---


### 2. **ANOVA Results Visualization**

**Description:**  
This visualization shows the results of the 2 ANOVA tests. 

*Q1:Does Innovation Performance of IS Project Teams significantly vary based on the levels of Innovation capability variables of wellbeing, cooperation, and competition ?*

*Q2: Does Innovation Performance of IS Project Teams significantly vary based on the levels of Process Innovation (innoprocess), Product Innovation (innoproduct), and Flexibility?*


---

### 4. **Linear Regression Analysis**

**Description:**  
Based on the results of two testes above the linear regression results are shown as below:

![image](https://github.com/user-attachments/assets/ccbae910-7e58-4e0a-b0eb-0e86099d0fe0) 


![image](https://github.com/user-attachments/assets/71df7310-c508-4fa4-9f9d-c29d2e0b206d) 


![image](https://github.com/user-attachments/assets/3a1caae0-0570-4689-a91c-a221635738c6) 





![image](https://github.com/user-attachments/assets/2c2270b6-35cd-439a-8e2d-e1b5bd27718a)


![image](https://github.com/user-attachments/assets/770600c8-b058-4529-a7a8-be4a302842ed)



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
