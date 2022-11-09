## Case Study: Loan Delinquent Analysis

### **Context:** 

-   DRS bank is facing challenging times. Their NPAs (Non-Performing Assets) have been on a rise recently and a large part of these are due to the loans given to individual customers(borrowers). The Chief Risk Officer of the bank decides to put in a scientifically robust framework for approval of loans to individual customers to minimize the risk of loans converting into NPAs and initiates a project for the data science team at the bank. You, as a senior member of the team, are assigned this project.

### **Problem:**

**The data-set aims to answer the following key questions:**

-   What are the factors leading to delinquency?
-   Does imbalance in the data affect model predictions?
-   What are the key business recommendations based on analysis and model?

### Attribute Information:

-   The data contains characteristics of the people
    
-   ID: Customer ID
    
-   isDelinquent : indicates whether the customer is delinquent or not (1 => Yes, 0 => No)
    
-   term: Loan term in months
    
-   gender: Gender of the borrower
    
-   age: Age of the borrower
    
-   purpose: Purpose of Loan
    
-   home\_ownership: Status of borrower's home
    
-   FICO: FICO (i.e. the bureau score) of the borrower
    

### **Learning Outcomes:**

-   Exploratory Data Analysis
-   K-fold Cross-validation
-   Handling imbalanced data
-   Regularization to reduce overfitting

### **Steps and Tasks:**

-   Import Libraries and Load Dataset

-   Overview of data
-   Data Visualization

-   Data preparation
-   Choose model
-   Over and under-sample train set to balance the classes
-   Perform regularization, if needed

-   Conclusion