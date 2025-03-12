# AllLife Bank - Personal Loan Prediction

## Context
AllLife Bank, a US-based financial institution, has a growing customer base, primarily consisting of **liability customers** (depositors). However, the number of **borrowers** (asset customers) is relatively small. The bank aims to expand its loan business by converting more depositors into **personal loan customers** while ensuring they remain depositors.  

A previous marketing campaign targeting liability customers achieved a **conversion rate of over 9%**, motivating the **retail marketing department** to develop more targeted campaigns to improve this success rate.  

As a **Data Scientist** at AllLife Bank, your task is to build a predictive model that helps the marketing team identify **potential customers** who are most likely to purchase a personal loan.

---

## Objective
The goal of this project is to:  
- **Predict** whether a liability customer will purchase a personal loan.  
- **Identify** key customer attributes that influence loan purchases.  
- **Segment** customers to improve targeted marketing strategies.  

---

## Data Description
The dataset contains information about customers, including their demographics, financial history, and loan purchase behavior.

### **Data Dictionary**
| Column Name          | Description |
|----------------------|-------------|
| `ID`                | Unique Customer ID |
| `Age`               | Customer’s age (in completed years) |
| `Experience`        | Years of professional experience |
| `Income`            | Annual income (in thousand dollars) |
| `ZIP Code`          | Home address ZIP code |
| `Family`            | Family size of the customer |
| `CCAvg`             | Average monthly credit card spending (in thousand dollars) |
| `Education`         | Education Level *(1: Undergrad, 2: Graduate, 3: Advanced/Professional)* |
| `Mortgage`          | Value of house mortgage (if any) (in thousand dollars) |
| `Personal_Loan`     | Whether the customer accepted a personal loan in the last campaign *(0: No, 1: Yes)* |
| `Securities_Account` | Does the customer have a securities account? *(0: No, 1: Yes)* |
| `CD_Account`        | Does the customer have a certificate of deposit (CD) account? *(0: No, 1: Yes)* |
| `Online`            | Does the customer use internet banking? *(0: No, 1: Yes)* |
| `CreditCard`        | Does the customer use a credit card issued by another bank (excluding AllLife Bank)? *(0: No, 1: Yes)* |

---

## Getting Started
To analyze and build a predictive model, follow these steps:

1. **Load the dataset** into a data analysis environment (e.g., Python, Jupyter Notebook).
2. **Perform exploratory data analysis (EDA)** to identify patterns and insights.
3. **Preprocess the data** (handle missing values, encode categorical variables, normalize features, etc.).
4. **Build and evaluate machine learning models** to predict loan purchases.
5. **Interpret the results** and provide insights for the marketing team.

---

## Tools & Technologies
Recommended tools for this project:

- **Python**
- **Jupyter Notebook**
- **Pandas, NumPy, Matplotlib, Seaborn** (for data analysis and visualization)
- **Scikit-learn** (for building predictive models)

---

## Contributing
If you have suggestions or improvements, feel free to submit a pull request!

---

## License
This project is licensed under the MIT License.
