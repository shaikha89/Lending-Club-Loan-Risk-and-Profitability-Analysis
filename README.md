![](https://riskonnect.com/wp-content/uploads/2024/04/Quantitative-Risk-Management-vs.-Qualitative-Risk-Analysis-1.jpg)
# Lending-Club-Loan-Risk-and-Profitability-Analysis
This project analyzes Lending Club loan data to explore credit risk, borrower behavior, and loan profitability. It uses Python visualizations to uncover patterns in loan grades, purposes, income levels, interest rates, and payment behavior to help identify safer, more profitable loans.
## 📌 Project Goals

- Understand **credit risk trends** in peer-to-peer lending.
- Measure **loan profitability** for investors.
- Analyze **borrower behavior** and repayment patterns.
- Identify factors affecting **default rates** and **late payments**.
- Provide clear, visual insights using **Python**, **Pandas**, **Matplotlib**, and **Seaborn**.

---

## 📈 Key Analyses

✔️ **Loan Status by Purpose**  
✔️ **Loan Grade by Risk**  
✔️ **Loan Amount and Interest Rate Trends**  
✔️ **Default Rates by Income Range**  
✔️ **Payment Behavior Over Time**  
✔️ **Installment Size vs. Loan Amount**  
✔️ **Profitability Analysis by Loan Status**  
✔️ **Employment Length, Home Ownership, and Risk Relationships**

---

## 🛠️ Tools Used

- **Python**
- **Pandas**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook**

---

## 📁 Dataset

- 📌 Lending Club loan data:  
  [Kaggle Dataset Link](https://www.kaggle.com/datasets/adarshsng/lending-club-loan-data-csv/data)

| Column Name              | Data Type   | Description                                                      |
|--------------------------|-------------|------------------------------------------------------------------|
| `id`                     | Object      | Unique identifier for each loan.                                |
| `loan_amnt`             | Float       | The amount of the loan.                                         |
| `term`                   | Object      | The term of the loan (e.g., 36 months, 60 months).            |
| `int_rate`               | Float       | The interest rate for the loan.                                |
| `installment`           | Float       | Monthly payment amount.                                        |
| `grade`                  | Object      | Loan grade assigned by Lending Club.                           |
| `sub_grade`              | Object      | More specific grade assigned to the loan.                      |
| `emp_title`              | Object      | Title of the borrower's job.                                   |
| `emp_length`             | Object      | Length of employment in years.                                 |
| `home_ownership`         | Object      | Home ownership status (e.g., RENT, OWN).                      |
| `annual_inc`             | Float       | Borrower's annual income.                                      |
| `verification_status`    | Object      | Verification status of the borrower's income.                  |
| `issue_d`                | DateTime    | Date when the loan was issued.                                 |
| `loan_status`            | Object      | Current status of the loan (e.g., Fully Paid, Charged Off).   |
| `purpose`                | Object      | Purpose of the loan (e.g., debt consolidation, home improvement). |
| `title`                  | Object      | Loan title provided by the borrower.                           |
| `zip_code`               | Object      | Borrower's zip code.                                          |
| `addr_state`             | Object      | State of the borrower's address.                               |
| `dti`                    | Float       | Debt-to-income ratio.                                         |
| `delinq_2yrs`           | Integer     | Number of delinquencies in the past 2 years.                  |
| `fico_range_low`        | Integer     | Lower bound of FICO score range.                              |
| `fico_range_high`       | Integer     | Upper bound of FICO score range.                              |
| `open_acc`              | Integer     | Number of open accounts.                                       |
| `pub_rec`               | Integer     | Number of derogatory public records.                           |
| `revol_bal`             | Float       | Total credit revolving balance.                                 |
| `revol_util`            | Float       | Revolving credit utilization.                                   |
| `total_acc`             | Integer     | Total number of credit accounts.                               |
| `initial_list_status`    | Object      | The initial listing status of the loan.                        |
| `total_pymnt`           | Float       | Total amount paid to date.                                    |
| `total_pymnt_inv`       | Float       | Total amount paid to investors.                                |
| `total_rec_int`         | Float       | Total amount of interest received to date.                    |
| `total_rec_late_fee`    | Float       | Total late fees received to date.                             |
| `recoveries`            | Float       | Amount recovered after a charge-off.                          |
| `collection_recovery_fee`| Float       | Fees collected from recovered loans.                           |
| `last_pymnt_d`          | DateTime    | Last payment date.                                           |
| `last_pymnt_amnt`       | Float       | Last payment amount.                                         |
| `next_pymnt_d`          | DateTime    | Next payment date.                                           |
| `last_credit_pull_d`    | DateTime    | Date of the last credit pull.                                 |
| `application_type`      | Object      | Type of application (Individual or Joint).                    |
| `chargeoff_within_12_mths` | Integer  | Indicator if the loan was charged off within 12 months.      |
| `delinq_amnt`           | Float       | Total amount of delinquent payments.                          |
| `pub_rec_bankruptcies`  | Integer     | Number of bankruptcies recorded.                              |



























---

## 📊 Future Improvements

- Build predictive models for loan defaults.
- Use machine learning classifiers (Logistic Regression, Random Forest, XGBoost).
- Optimize profitability predictions based on borrower profiles.
- Automate dashboard reporting for investors.
  
---

## 📜 License

This project is for educational and non-commercial use.
