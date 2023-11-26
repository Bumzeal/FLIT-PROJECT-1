# FLIT-PROJECT- MARKET BASKET ANALYSIS


## TASK OBJECTIVE
The goal of this project is to introduce you to the concept of market basket analysis, which is a crucial aspect of data science in retail and e-commerce. You will learn how to extract valuable insights from transaction data, understand customer purchasing behavior, and use this knowledge for business optimization.

## TOOLS USED FOR THE PROJECT
* Data Analysis Tool (Python: using Libries such as Pandas)
* Data Visualisation (Matplotlib & Seaborn)
* Scikit-Learn
* APriori Algorithm
* Jupyter Notebook
  
## OUTLINE 
1. Data Preparation
2. Exploratory Data Analysis (EDA)
3. Market Basket Analysis
4. Visualization
5. Interpretation and Insights
6. Recommendations

## Deliverables 
A well-documented  Jupyter  Notebook  or  report  containing  code  and explanations.

•  Visualizations that support your findings.
•  A presentation or report for your mentorship group.
•  A GitHub repository with documentation and code.

### IMPORT NECESSARY LIBRARIES AND OS

![image](https://github.com/Bumzeal/FLIT-PROJECT-1/assets/78567274/b1fde7c0-aa33-4617-bb1c-6fcdb987a6c4)



### DATA PREPARATION

1. Loading data from source-Desktop
2. Viewing Top 10 Data 
3. Checking the Total number of Row and columns, Datatypes
4. checking missing Value

### LOAD DATA 

![image](https://github.com/Bumzeal/FLIT-PROJECT-1/assets/78567274/bf51e6e6-385c-47c8-8c62-88405c972311)


### PERFORMING TRANSACTIONAL ENCODING

Transaction encoding is the process of converting transactional data into a binary matrix format where rows represent transactions and columns represent unique items. Each cell in the matrix indicates whether a particular item was present (1) or absent (0) in a transaction. 

### APRIORI ALGORITHM
To use the Apriori algorithm for transactional data in Python, you can use the mlxtend library, which provides a convenient implementation of the Apriori algorithm. Here's a step-by-step guide:
