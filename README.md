# Lead-Scoring-Case-Study


This repository contains the code and documentation for building a logistic regression model to assign a lead score to each of the leads in order to identify potential customers who are most likely to convert into paying customers. The model aims to improve the lead conversion rate and optimize the sales team's efforts.

### Problem Statement
X Education, an online education company, faces challenges with their lead conversion process. Despite generating a significant number of leads, the company's lead conversion rate is poor. To address this issue, the company wants to identify the most potential leads, referred to as 'Hot Leads,' to improve the lead conversion rate. By focusing on communicating with the potential leads, rather than reaching out to every lead, the company aims to increase the efficiency of their lead conversion process.

The primary goal of this case study is to build a logistic regression model that assigns a lead score between 0 and 100 to each lead. The lead score indicates the likelihood of a lead converting into a paying customer, with higher scores indicating hotter leads and lower scores indicating colder leads. Additionally, the CEO has set a target lead conversion rate of around 80%.

### Data
The dataset provided for this case study contains approximately 9000 data points, each representing a lead. The dataset includes various attributes such as Lead Source, Total Time Spent on Website, Total Visits, Last Activity, etc. These attributes may be useful in determining whether a lead will convert or not. The target variable is the 'Converted' column, which indicates whether a lead was converted (1) or not converted (0).

It is important to note that some categorical variables in the dataset have a level called 'Select,' which is equivalent to a null value. Handling these 'Select' levels appropriately is necessary during the data preprocessing phase.

### Goals of the Case Study
The following goals should be achieved through this case study:

Build a logistic regression model to assign a lead score between 0 and 100 to each lead. The lead score will help identify potential leads and prioritize sales efforts.

Address additional problems presented by the company. The logistic regression model should be flexible enough to accommodate future changes in the company's requirements. These additional problems are outlined in a separate document, which should be filled based on the logistic regression model developed in the first step. The recommendations derived from the model should also be included in the final presentation (PPT).


### Dependencies

The following dependencies are required to run the code in this repository:

Python 3.7+

NumPy

pandas

scikit-learn

Matplotlib

Jupyter Notebook

Please ensure that these dependencies are properly installed before running any code.
