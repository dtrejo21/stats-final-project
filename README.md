# Credit Card Approvals Project (Stats 3 Final Project)

## Project Team Members
- Guilherme Camara
- Luis Infante
- Matthew Labrada
- Daisy Trejo-Hernandez

## Motivation
Our research aims to explore the factors influencing credit card approval decisions. Understanding these factors can significantly impact financial institutions' decision-making processes and help potential applicants improve their chances of approval. This study seeks to identify key variables that contribute to the approval or rejection of credit card applications, providing insights that could be beneficial for both lenders and borrowers.

## Data Description
The dataset used in this study is a cleaned and labeled version of the UCI Machine Learning Repository's Credit Approval dataset. The cleaned dataset can be found on Kaggle: [Credit Card Approval Clean Data](https://www.kaggle.com/datasets/samuelcortinhas/credit-card-approval-clean-data/data), originally sourced from [UCI's archive](https://archive.ics.uci.edu/ml/datasets/Credit+Approval).

This dataset includes a variety of variables related to credit card applications, such as age, income, debt, credit score, and more, making it a comprehensive resource for analyzing credit approval factors. The data was collected to understand the underlying patterns in credit card approvals, with the cleaning process ensuring the dataset is more accessible and applicable for such studies.

## Basic Data Analysis
Our initial analysis focused on understanding the distribution, relationships, and potential impact of each variable on credit card approvals. Through histograms, box plots, and correlation matrices, we identified several variables that show promising predictive capabilities, such as income level, debt, and credit score.

- **Outliers**: Preliminary analysis revealed a few outliers in variables like income and debt, which will require further investigation to determine their impact on our models.
- **Collinearity**: We observed some degree of collinearity between variables like income and credit score, which may affect our analysis and will need to be addressed.
- **Variable Transformations**: Given the skewness in some of the distributions, we're considering applying transformations to achieve normality.
- **Potential Interactions**: We plan to explore interaction terms, especially between demographic variables and financial metrics, to better capture their combined effect on credit card approval.

## Future Direction
For the full analysis, our goal is to develop a predictive model that accurately identifies the key factors leading to credit card approval. We plan to employ various statistical techniques and machine learning models to analyze the data further. The next steps include more in-depth analysis to handle outliers, multicollinearity, and the implementation of potential transformations and interaction terms. Ultimately, we hope to derive actionable insights that can be applied to improve credit approval processes.

## Works Cited
- Samuel Cortinhas, “Credit Card Approval Clean Data,” Kaggle, [https://www.kaggle.com/datasets/samuelcortinhas/credit-card-approval-clean-data/data](https://www.kaggle.com/datasets/samuelcortinhas/credit-card-approval-clean-data/data).
- Dua, D. and Graff, C. (2019). UCI Machine Learning Repository [https://archive.ics.uci.edu/ml/datasets/Credit+Approval](https://archive.ics.uci.edu/ml/datasets/Credit+Approval). Irvine, CA: University of California, School of Information and Computer Science.

## Contribution Statement
We, the project team members, certify that below is an accurate account of the percentage of effort contributed by each team member in the project and report.

| Project Team Member  | Percentage of Total Effort |
|----------------------|----------------------------|
| Guilherme Camara     |                            |
| Luis Infante         |                            |
| Matthew Labrada      |                            |
| Daisy Trejo-Hernandez|                            |

**Note**: Although the project guidelines mention using R, our analysis was conducted using Python due to our collective proficiency and the powerful libraries available for data analysis in Python.
