# Problem Definition:

A machine learning model is to be developed to predict customers who are likely to churn (leave the company). Before building the model, it is essential to perform data analysis and feature engineering steps.

The Telco customer churn dataset contains information about 7,043 customers of a fictional telecommunications company that provides home phone and internet services in California during the third quarter. It includes details about whether a customer has stayed, left, or signed up for the service.

# Dataset Information:

21 Variables, 7,043 Observations. Each row represents a unique customer. The variables include information on customer services, account details, and demographics. Services include: phone service, multiple lines, internet, online security, online backup, device protection, tech support, streaming TV and movies. Account details: tenure, contract type, payment method, paperless billing, monthly and total charges. Demographics: gender, senior citizen status, partner, and dependents.

# TASK 1: EXPLORATORY DATA ANALYSIS (EDA)

Step 1: Examine the overall structure of the dataset Step 2: Identify numerical and categorical variables Step 3: Analyze numerical and categorical variables Step 4: Analyze the target variable (Mean churn by categorical variables, Mean of numerical variables by churn) Step 5: Perform outlier detection Step 6: Analyze missing values Step 7: Perform correlation analysis

# TASK 2: DATA CLEANING

Step 1: Apply necessary procedures for missing and outlier values

## TASK 3: Feature Engineering, Encoding & Modeling

1. **Feature Engineering**  
   - Generated new features such as interaction terms and ratios.

2. **Encoding & Scaling**  
   - Applied **One-Hot Encoding** for categorical variables.  
   - Combined rare categories where necessary.  
   - Scaled numerical features using **StandardScaler**.

3. **Modeling**  
   - Built a **Random Forest Classifier** for churn prediction.

4. **Model Evaluation**  
   - Evaluated the model using **Accuracy Score**.  
   - Generated a **Classification Report** including precision, recall, and F1-score.

---

## Tools & Libraries

- **Python**  
- **Pandas, NumPy** (data analysis)  
- **Scikit-learn** (modeling, encoding, scaling)  
- **Matplotlib, Seaborn** (visualization)

---

## Results

The Random Forest model provided insights into key factors driving customer churn and achieved strong performance based on standard classification metrics.
