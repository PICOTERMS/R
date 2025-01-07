
This repository contains the project file Innovation Capabilities of IS Project Teams.qmd, which analyzes the innovation capabilities of IS project teams. The analysis is based on a structured questionnaire that evaluates six dimensions of IT project paradoxes. The final report includes statistical insights, visualizations, and regression models.

Project Overview
Objective:
The primary goal of this project is to study the key factors influencing the innovation capabilities of IS project teams. Using quantitative methods, the data collected from a structured questionnaire has been analyzed to uncover patterns and relationships.

Data:
Source: Questionnaire with six dimensions of IT project paradoxes.
Format: CSV file with:
12 numerical variables
3 categorical variables
Dimensions Evaluated:
Work atmosphere during the project
Socialisation and collaboration
Project coordination
Knowledge sharing and management
Project performance
Project characteristics
Methodology
The analysis follows these steps:

Data Loading and Preprocessing:

Cleaned and prepared the dataset for analysis.
Handled missing values and ensured consistency across variables.
Descriptive Analysis:

Computed measures such as mean, variance, and distribution.
Visualizations include bar charts, histograms, and box plots.
Inferential Analysis:

Conducted ANOVA tests to identify group differences.
Performed linear regression modeling to explore relationships between variables.
Visualization:

Created detailed static plots (e.g., histograms, scatter plots) using ggplot2.
Added interactive plots with plotly for better exploration.
Results:

Identified significant relationships between project dimensions.
Regression equations provided insights into the factors driving innovation.
Outputs
Main Deliverables:
HTML Report:
A self-contained report summarizing the entire analysis, ready to share or view in any browser.
Visualizations:
Graphs and plots to represent trends, distributions, and relationships within the data.
Key Findings:
Insightful summaries of the statistical analysis and regression results.
Repository Structure
Innovation Capabilities of IS Project Teams.qmd: The main Quarto Markdown file containing the analysis code and documentation.
report.html: The final self-contained HTML report.
PARA5.csv: The dataset used for analysis.
README.md: This documentation file.
How to View the Results
Clone this repository:
bash
Copy code
git clone https://github.com/USERNAME/REPOSITORY_NAME.git
Open the report.html file in any browser to view the analysis and results.
Adding Visuals to README
If you wish to include images or plots in the README file (e.g., sample visualizations from the analysis), follow these steps:

Save the plot or chart as an image (e.g., png or jpg).
Upload the image to the repository (e.g., in an images folder).
Reference the image in the README using Markdown syntax:
markdown
Copy code
![Sample Visualization](images/sample_plot.png)
Example:
Packages Used
Data Processing:
readr, dplyr, tidyr
Visualization:
ggplot2, plotly
Statistical Analysis:
lmtest, car, psych
Rendering:
quarto, rmarkdown, knitr
How to Reproduce
Install required packages:
r
Copy code
install.packages(c("readr", "dplyr", "tidyr", "ggplot2", "plotly", "lmtest", "car", "psych", "quarto", "rmarkdown", "knitr"))
Open the Innovation Capabilities of IS Project Teams.qmd file in RStudio or a Quarto-supported editor.
Render the file:
bash
Copy code
quarto render "Innovation Capabilities of IS Project Teams.qmd"
این نسخه کاملاً توضیح‌دهنده است. اگر تصویری خاص یا نموداری می‌خواهید اضافه کنید، می‌توانید با روش ذکرشده این کار را انجام دهید. همچنین اگر بخواهید قسمتی اصلاح شود، اطلاع دهید!





You said:
خب اونجاهایی که قراره شکل بذارم توضیحات بالاش بنویس لطفا مثلا راجع به اینکه توی این بخش چکار کردیم و زیر تصویر بذارم 
ChatGPT said:

بسیار خوب! می‌توانید توضیحات مربوط به بخش‌هایی که نیاز به نمودار یا تصویر دارند را به شکل زیر در فایل README.md بگنجانید. این توضیحات به طور دقیق مشخص می‌کند که چه کاری در آن بخش انجام شده و تصویر چگونه به درک بهتر تحلیل کمک می‌کند.

1. Data Distribution Visualization
Description:
In this section, we visualized the distribution of key numerical variables in the dataset. The histogram below shows the distribution of Project Performance scores, helping us understand the tendency and spread of responses across the scale.

Example Markdown for README:

markdown
Copy code
### Data Distribution Visualization

In this section, we visualized the distribution of key numerical variables in the dataset. The histogram below shows the distribution of **Project Performance** scores, helping us understand the tendency and spread of responses across the scale.

![Histogram of Project Performance](images/project_performance_histogram.png)
2. Correlation Matrix
Description:
To understand the relationships between different numerical variables, a correlation matrix was created. The heatmap below highlights the strength and direction of relationships between variables such as Work Atmosphere, Collaboration, and Project Coordination.

Example Markdown for README:

markdown
Copy code
### Correlation Matrix

To understand the relationships between different numerical variables, a correlation matrix was created. The heatmap below highlights the strength and direction of relationships between variables such as **Work Atmosphere**, **Collaboration**, and **Project Coordination**.

![Correlation Matrix](images/correlation_matrix.png)
3. ANOVA Results Visualization
Description:
This section visualizes the results of the ANOVA tests performed on different categorical variables to examine group differences. The box plot below shows the variation in Project Performance across different Project Characteristics categories.

Example Markdown for README:

markdown
Copy code
### ANOVA Results Visualization

This section visualizes the results of the ANOVA tests performed on different categorical variables to examine group differences. The box plot below shows the variation in **Project Performance** across different **Project Characteristics** categories.

![Box Plot for ANOVA Results](images/anova_boxplot.png)
4. Linear Regression Analysis
Description:
Linear regression analysis was used to model the relationship between Project Coordination and Project Performance. The scatter plot below, with a fitted regression line, shows the strength and direction of this relationship.

Example Markdown for README:

markdown
Copy code
### Linear Regression Analysis

Linear regression analysis was used to model the relationship between **Project Coordination** and **Project Performance**. The scatter plot below, with a fitted regression line, shows the strength and direction of this relationship.

![Linear Regression Plot](images/linear_regression_plot.png)
