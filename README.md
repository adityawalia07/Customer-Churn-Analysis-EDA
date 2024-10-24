# Customer-Churn-Analysis-EDA
This project performs exploratory data analysis (EDA) on a customer churn dataset to gain insights into customer behavior and factors influencing churn.

## Table of Contents
- Project Overview
- Dataset Information
- Installation
- Usage
- Analysis Highlights
- Technologies Used
- Contributing
- License

## Project Overview
The goal of this project is to explore the factors leading to customer churn.<br> Using various exploratory data analysis techniques, the notebook highlights important features and patterns that help in understanding customer retention and churn rates.

## Dataset Information
The dataset used in this analysis contains customer information along with whether or not the customer churned in the last month.<br> 
#### Key features include:
- CustomerID
- SeniorCitizen (Categorical)
- Monthly Charges
- Tenure
- Contract type
- Payment method

#### This dataset is highly imbalanced with a churn ratio of approximately 73:27.

## Installation
To run this project, follow these steps:

### Clone the repository:
```bash
Copy code
git clone https://github.com/yourusername/customer-churn-eda.git
```
### Navigate to the project directory:
```bash
Copy code
cd customer-churn-eda
```

## Usage
To explore the dataset and reproduce the analysis, simply run the provided Jupyter notebook:

## Key insights from the analysis include:

- Distribution of Senior Citizens: The dataset contains a binary categorical variable for Senior Citizens, which has been analyzed for its impact on churn.<br>
- Monthly Charges vs. Churn: Customers with higher monthly charges show a higher churn rate.<br>
- Tenure Analysis: 75% of the customers have a tenure of less than 55 months, with a detailed look at how tenure correlates with churn.<br>
## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
## Contributing
Feel free to open issues or submit pull requests if you'd like to contribute to the project.

