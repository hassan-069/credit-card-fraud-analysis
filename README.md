# credit-card-fraud-analysis
Credit Card Fraud Detection Dataset

## Project Overview:
This project performs an exploratory data analysis (EDA) on a credit card transaction dataset to identify fraudulent transactions. The dataset is sourced from Kaggle and contains a mix of legitimate and fraudulent transaction records.

### Dataset Source:
- **Kaggle Dataset:** [Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

---

## Dataset Summary:
- **Total Rows:** 284,807
- **Total Columns:** 31

### Key Columns:
- **Amount**: Represents the transaction amount. (Float type)
- **Class**: Indicates whether the transaction is fraudulent (1) or legitimate (0). (Integer type)
- Other columns involve various transaction features such as time and transaction numbers, primarily in float format.

---

## Data Quality:
- **Missing Values:** No missing or null values were found in the dataset.
  
---

## Transaction Analysis:
- **Legitimate Transactions:** 284,315
- **Fraudulent Transactions:** 492

### Fraudulent Transaction Percentage:
Fraudulent transactions account for approximately 0.17% of the total transactions in the dataset.

---

## Statistical Summary for 'Amount':
- **Minimum:** 0.0
- **Maximum:** 25,691.16
- **Mean:** 88.35
- **Median:** 22.0

---

## Transaction Amount Insights:
- **Maximum Transaction Amount:** 25,691.16
- **Fraudulent or Legitimate?**: This maximum transaction amount is legitimate.

---

## Visualization:
### Bar Chart for Transaction Count:
While creating a bar chart for fraudulent vs. legitimate transactions is possible, it’s not recommended in this case due to the extreme imbalance in the data (with fraudulent transactions being significantly fewer). This type of visualization does not effectively display the distribution of these two categories.

### Histogram of Transaction Amounts:
The histogram reveals that most transaction amounts fall within the range of 0 to 5,000. The graph is **right-skewed**, indicating that the tail of the distribution extends toward higher values.

### Correlation Analysis:
Given the nature of the dataset, a heatmap for correlation analysis isn’t the best approach. Many of the transaction-related columns (such as transaction numbers and times) are not correlated. Instead, a **scatter plot** can be more effective for visualizing the relationships between numerical features.

---
## How to Run the Code

1. **Clone the repository:**
   ```bash
   git clone https://github.com/hassan-069/credit-card-fraud-analysis.git
