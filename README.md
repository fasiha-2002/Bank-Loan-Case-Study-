# Bank-Loan-Case-Study-
Project Description: 
This case study aims to give us an idea of applying EDA in a real business scenario. In this case study, we will develop a basic understanding of risk analytics in banking and financial services and understand how data is used to minimize the risk of losing money while lending to customers. 

Business Understanding: 
The loan-providing companies find it hard to give loans to people due to their insufficient or non-existent credit history. Because of that, some consumers use it to their advantage by becoming defaulters. 

➢ How are we going to handle things? 
Suppose we work for a consumer finance company that specializes in lending various types of loans to urban customers. We will use EDA to analyze the patterns present in the data. This will ensure that the applicants capable of repaying the loan are accepted. 

➢ When the company receives a loan application, the company has to decide on loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision: 
• If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company.
• If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company. 

➢ When a client applies for a loan, four types of decisions could be taken by the client/company: 
1. Approved: The company has approved the loan application 
2. Cancelled: The client canceled the application sometime during approval. Either the client changed her/his mind about the loan or in some cases due to a higher risk the client received worse pricing which he did not want. 
3. Refused: The company had rejected the loan (because the client does not meet their requirements etc.). 
4. Unused Offer: The loan has been canceled by the client but is in different stages of the process. 

In this case study, we will use EDA to understand how consumer attributes and loan attributes influence the tendency of default.

➢ Following are the things that we are going to find out through this case study: 
•We aim to identify the patterns which indicate if a client has difficulty paying their installments which may be used for taking actions such as denying the loan, reducing the amount of the loan, lending (to risky applicants) at a higher interest rate, etc. 
• The driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default. 
• Presenting the overall approach of the data analysis, cleaning the dataset, finding outliers, data imbalance, univariate, segmented univariate, bivariate analysis, etc. 
• The top 10 correlations for the Client with payment difficulties and all other cases (Target variable).

Tech-Stack Used: 
• Jupyter Notebook: It is used for data cleaning and imputing the data. As the dataset was very large, it is used for the whole data analysis purpose, visualizing the data and summarizing it to get the necessary insights for the client. 
• Python Programming (Version 3.8): For data analysis, python is the best and the easiest-to-use programming language

Present the overall approach of the analysis. Mention the problem statement and the analysis approach briefly

Statement: This case study aims to identify patterns which indicate if a client has difficulty paying their installments which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc. This will ensure that the consumers capable of repaying the loan are not rejected. Identification of such applicant’s using EDA is the aim of this case study.
The dataset given by the client contains the information about the loan application at the time of applying for the loan. It contains two types of scenarios: 
• The client with payment difficulties: he/she had late payment more than X days on at least one of the first Y instalments of the loan in our sample 
• All other cases: All other cases when the payment is paid on time. We will use EDA to understand how consumer attributes and loan attributes influence the tendency of default

Analysis Approach: 
Following steps done for the analysis purpose: 
• Imported the NumPy, pandas, matplotlib and seaborn python libraries. 
• Imported the datasets (Application_Data & Previous_Application) 
• Identification: We have identified how we will approach the data, finding missing dataset and working on it accordingly to gain the required results. 
• Outliers: Identified outliers and showed how they play if any role in our dataset. 
• Imbalance: Understanding the ratio of imbalance in our data. 
• Correlation Analysis: Finding the correlation between the variables with respect to the target variables and find the top three correlation. 
• Visualisation: Visualized the data with the help of charts and graphs
