# 📊 Loan Eligibility Analysis  

This project analyzes a dataset containing information about loans and customer profiles to determine **loan eligibility** and understand the factors influencing loan status.  

---

## 📁 Dataset Overview  

The dataset contains **100,000 records** and the following **19 features**:  

### 1️⃣ **Loan Information**  
- **Loan ID**: Unique identifier for a customer's loan.  
- **Customer ID**: Unique identifier for a customer.  
- **Loan Status**:  
  - `chargedOff`: The loan is in default, and no further payment is expected.  
  - `fullPaid`: The loan has been fully repaid.  
- **Current Loan Amount**: The principal balance of the loan.  
- **Term**: Indicates whether the loan is long-term or short-term.  

### 2️⃣ **Customer Financial Profile**  
- **Credit Score**: The customer's creditworthiness score.  
- **Annual Income**: Annual income of the customer.  
- **Monthly Debt**: The customer's monthly debt payments.  
- **Current Credit Balance**: The current balance on the customer's credit card.  
- **Maximum Open Credit**: Maximum credit limit available on the customer's credit card.  

### 3️⃣ **Customer Employment and Residence**  
- **Years in Current Job**: Number of years the customer has been in their current job.  
- **Home Ownership**: The type of home ownership (e.g., own, mortgage, rent).  

### 4️⃣ **Credit History and Issues**  
- **Years of Credit History**: The length of the customer's credit history in years.  
- **Months Since Last Delinquent**: Number of months since the customer last defaulted on an EMI.  
- **Number of Open Accounts**: Total number of open accounts (e.g., savings, current).  
- **Number of Credit Problems**: The number of credit-related issues (e.g., late payment penalties).  
- **Bankruptcies**: The number of times the customer has filed for bankruptcy.  
- **Tax Liens**: The number of tax liens imposed on the customer.  

### 5️⃣ **Loan Purpose**  
- **Purpose**: The reason for taking out the loan (e.g., debt consolidation, home improvement).  

---

## 🛠️ Steps in Analysis  

### 🔹 **Data Preprocessing**  
- Handle missing values.  
- Encode categorical variables.  
- Normalize numerical features.  

### 🔹 **Exploratory Data Analysis (EDA)**  
- Analyze distributions of features.  
- Identify correlations between features and loan status.  

### 🔹 **Feature Engineering**  
- Create new features (e.g., debt-to-income ratio, credit utilization).  

### 🔹 **Modeling**  
- Split the data into training and testing sets.  
- Train classification models to predict loan status (`chargedOff` or `fullPaid`).  

### 🔹 **Evaluation**  
- Evaluate model performance using metrics like **accuracy**, **precision**, **recall**, and **F1-score**.  

---

## 🎯 Expected Outcomes  
1. **Identify key factors** influencing loan eligibility.  
2. Develop a **predictive model** for loan status (charged off or fully paid).  

---

## 🚀 Getting Started  

### Prerequisites  
Ensure the following libraries are installed:  
- 📦 **Pandas**: For data manipulation.  
- 📦 **NumPy**: For numerical operations.  
- 📦 **Matplotlib/Seaborn**: For data visualization.  
- 📦 **scikit-learn**: For machine learning models and preprocessing.  

### Installation  
Run the following command to install any missing libraries:  
```bash  
!pip install pandas numpy matplotlib seaborn scikit-learn  
