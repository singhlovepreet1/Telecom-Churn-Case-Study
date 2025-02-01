# Telecom Churn Case Study

## Overview
In the telecom industry, customers can choose from multiple service providers and actively switch from one operator to another. In this highly competitive market, the telecommunications industry experiences an average of 15-25% annual churn rate. Given the fact that it costs 5-10 times more to acquire a new customer than to retain an existing one, customer retention has now become even more important than customer acquisition.

The telecom industry has identified two types of churn:

1. **Revenue-based churn** – Customers who generate minimal revenue over a period.
2. **Usage-based churn** – Customers who have not used any services (calls, SMS, or data) for a given duration.

The focus of this project is on **usage-based churn prediction** and identifying **high-value customers**, who contribute 80% of industry’s revenue. This can be done by analyzing customer data and building a predictive model that can help telecom companies retain customers by identifying those at risk of leaving and the main churn indicators.


## Dataset
The dataset contains customer-level information over four consecutive months: June, July, August, and September (encoded as 6, 7, 8, and 9). The goal is to predict churn in the ninth month using data from the first three months.

Key features include:

- Customer ID
- Monthly revenue and usage statistics
- Call, SMS, and data usage details
- High-value customer status
- Churn label for the ninth month (target variable)

To run the python notebook, first download the datafile from [here](https://drive.google.com/file/d/15LSuiE_Ap_cogPagOovo5ETxIMT2GbmM/view?usp=sharing)
 and store it inside the data folder. The data set is available in a csv file named “Company Data.csv” and the data dictionary has been provided in a separate file named “DataDictionary.csv”. The data dictionary contains the meanings of the abbreviations.


## Project Workflow

1. **Data Preprocessing**
   - Cleaning missing values
   - Feature engineering and selection
   - Identifying high-value customers
   - Addressing class imbalance

2. **Exploratory Data Analysis (EDA)**
   - Understanding customer behavior before churning
   - Visualizing trends and patterns

3. **Model Development**
   - Logistic Regression (with and without PCA)
   - Support Vector Machine (SVM)
   - Decision Tree
   - Random Forest (with hyperparameter tuning)

4. **Model Evaluation**
   - Comparing models using accuracy, precision, recall, and F1-score
   - Identifying the most important features contributing to churn

5. **Final Model Selection**
   - Based on performance metrics, computational efficiency, interpretability, and feature importance

6. **Business Insights**
   - Suggestions for the telecom industry on which steps they can follow or offers they can provide to customers who are about to churn.


## How to run
To run this project, install the required dependencies using:

```bash
pip install -r requirements.txt
```


### Key Libraries Used:
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn


## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/singhlovepreet1/telecom-churn-case-study.git
   ```
2. Navigate to the project directory:
   ```bash
   cd telecom-churn-prediction
   ```
3. Run the Jupyter Notebook to execute the analysis:
   ```bash
   jupyter notebook Telecom_Churn_Prediction.ipynb
   ```

