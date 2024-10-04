# Workbench-SAS-Analytical-Process

# SAS Notebook - Real Estate Loan 
##  Analytical Modeling Process

**In this SAS notebook, we will go through all the steps of developing a predictive model.**

**The Steps are:**

*1) Data Preparation*

- Two different files are imported and then these files are joined. Next, a new variable is created.
- Identification of missing values ​​and imputation
- Several descriptive analyzes are carried out on the data for a good understanding

*2) Adjustment of the Predictive Model*
- A Decision Tree model (CART) is adjusted with the BAD variable as target
- Some checks are made regarding the quality of the model

*3) Model Registration in SAS Model Manager*
- Proc Registermodel is used to register the adjusted model in SAS Model Manager
- This is done to allow the user excute the entire subsequent ModelOps in SAS Viya


