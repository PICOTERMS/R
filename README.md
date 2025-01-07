Innovation Capabilities of IS Project Teams
This repository contains the project file Innovation Capabilities of IS Project Teams.qmd, which analyzes the innovation capabilities of IS project teams based on a structured questionnaire. The analysis includes both descriptive and inferential statistical methods, supported by visualizations and regression modeling.

Project Overview
Objective:
The primary goal of this project is to explore factors influencing innovation capabilities in IS project teams. Using quantitative methods, the data collected from a questionnaire has been analyzed to uncover patterns and relationships.

Data:
Source: Questionnaire with six dimensions of IT project paradoxes:
Work atmosphere during the project
Socialisation and collaboration
Project coordination
Knowledge sharing and management
Project performance
Project characteristics
Format: CSV file with:
12 numerical variables
3 categorical variables
Methodology
The analysis follows these steps:

Data Loading and Preprocessing:

Imported the dataset (PARA5.csv) and prepared it for analysis.
Addressed missing values and ensured data consistency.
Descriptive Analysis:

Measures such as mean, variance, and distribution were computed.
Visualizations were created to explore the spread and tendency of data.
Inferential Analysis:

ANOVA Tests: Conducted to examine significant group differences.
Linear Regression Modeling: Explored relationships between numerical variables.
Visualization:

Static plots (e.g., histograms, box plots) using ggplot2.
Interactive plots with plotly for deeper insights.
Results:

Identified significant patterns and relationships.
Regression equations provided quantitative insights into innovation factors.
Key Outputs
HTML Report:
A self-contained report summarizing the entire analysis.
Visualizations:
Graphs and plots to illustrate trends and relationships in the data.
Key Findings:
Insightful summaries of statistical analysis and regression results.
Visualizations
1. Data Distribution Visualization
Description:
This section visualizes the distribution of key numerical variables. The histogram below illustrates the distribution of Project Performance, showing the spread and central tendency of responses.


2. Correlation Matrix
Description:
To understand the relationships between numerical variables, a correlation matrix was created. The heatmap below highlights the strength and direction of relationships between variables.


3. ANOVA Results Visualization
Description:
This visualization shows the results of the ANOVA tests. The box plot below highlights variations in Project Performance across different Project Characteristics categories.


4. Linear Regression Analysis
Description:
The scatter plot below, along with the regression line, demonstrates the relationship between Project Coordination and Project Performance, providing insights into the strength and direction of the association.


Repository Structure
Innovation Capabilities of IS Project Teams.qmd: The main Quarto Markdown file containing the analysis code and documentation.
report.html: The final self-contained HTML report.
PARA5.csv: The dataset used for analysis.
images/: Folder containing all visualizations.
README.md: This documentation file.
How to View the Results
Clone this repository:
bash
Copy code
git clone https://github.com/USERNAME/REPOSITORY_NAME.git
Open the report.html file in any browser to view the analysis and results.
Required Packages
Data Processing:
readr, dplyr, tidyr
Visualization:
ggplot2, plotly
Statistical Analysis:
lmtest, car, psych
Rendering:
quarto, rmarkdown, knitr
Install these packages in R:

r
Copy code
install.packages(c("readr", "dplyr", "tidyr", "ggplot2", "plotly", "lmtest", "car", "psych", "quarto", "rmarkdown", "knitr"))
How to Reproduce
Open the Innovation Capabilities of IS Project Teams.qmd file in RStudio or a Quarto-supported editor.
Render the file:
bash
Copy code
quarto render "Innovation Capabilities of IS Project Teams.qmd"
