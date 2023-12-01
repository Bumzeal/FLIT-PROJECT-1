# FLIT-PROJECT- MARKET BASKET ANALYSIS


## TASK OBJECTIVE
Association Rule Mining is a data mining technique that discovers interesting relationships, patterns, or associations within large datasets. It aims to identify rules that describe how certain items or events tend to co-occur. One of the most common applications of association rule mining is in the analysis of transactional data

The primary goal of Association Rule Mining is to reveal hidden patterns in the data, enabling businesses and researchers to gain insights into the relationships between different variables. The classic example is market basket analysis which is a crucial aspect of data science in retail and e-commerce, and the goal is to discover which products are frequently purchased together


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

*  Visualizations that support your findings.
*  A presentation or report for your mentorship group.
*  A GitHub repository with documentation and code.

### IMPORT NECESSARY LIBRARIES AND OS

![image](https://github.com/Bumzeal/FLIT-PROJECT-1/assets/78567274/b1fde7c0-aa33-4617-bb1c-6fcdb987a6c4)



### DATA PREPARATION

1. Load data from source-Desktop
2. Show Top 10 Data 
3. Check the Total number of Row and columns and Datatypes
4. check For missing Value

## LOAD DATA 

![image](https://github.com/Bumzeal/FLIT-PROJECT-1/assets/78567274/bf51e6e6-385c-47c8-8c62-88405c972311)

## EXPLORATORY DATA ANALYSIS

## MARKET BASKET ANALYSIS

Market basket analysis provides oppurtunity to see The relationships between different variables. Here we'll discover which products are frequently purchased together


## PERFORMING TRANSACTIONAL ENCODING

Transaction encoding is the process of converting transactional data into a binary matrix format where rows represent transactions and columns represent unique items. Each cell in the matrix indicates whether a particular item was present (1) or absent (0) in a transaction. 
### APRIORI ALGORITHM
To use the Apriori algorithm for transactional data in Python, you can use the mlxtend library, which provides a convenient implementation of the Apriori algorithm. Here's a step-by-step guide:

