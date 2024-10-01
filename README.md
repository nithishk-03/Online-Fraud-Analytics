# Online-Fraud-Analytics

## Project Overview
The Online Fraud Analytics project aims to provide a comprehensive analysis of fraudulent transactions using a dataset from the National Payments Corporation of India (NPCI). This analysis focuses on identifying patterns, trends, and potential indicators of fraud in transaction data. 
## Objectives:

1. Data Cleaning and Preprocessing: Handling missing values, erroneous entries, and transforming categorical variables into numerical representations suitable for analysis.

2. Exploratory Data Analysis (EDA): Using statistical and visual techniques to understand the underlying patterns and distributions in the data. This includes examining transaction types, statuses, and error codes associated with fraudulent activities.

3. Visualization: Creating insightful visual representations of the data to make findings accessible and understandable. Visualizations include bar charts, box plots, and heatmaps to illustrate correlations among variables.

4. Insights and Recommendations: Drawing meaningful conclusions from the analysis, which can help stakeholders identify high-risk transaction patterns and improve fraud detection systems.

### Dataset Column Explanations

- **txn_id**: Unique identifier for each transaction, allowing for tracking and analysis.
- **txn_type**: Type of transaction (e.g., payment, transfer), useful for understanding the nature of the transaction.
- **txn_status**: Status of the transaction (e.g., success, failure, pending), indicating its outcome.
- **error_code**: Code representing any error that occurred during the transaction, helping to identify failure reasons.
- **payer_app**: Application used by the payer for the transaction (e.g., PayPal, Samsung Pay), useful for analyzing trends based on platforms.
- **payee_app**: Application used by the payee for the transaction, providing insights into user behavior.
- **payee_requested_amount**: Amount requested by the payee for the transaction, which can be compared to the settled amount.
- **payee_settlement_amount**: Amount that was settled in the transaction after processing, important for understanding transaction success.
- **payer_location**: Geographic location of the payer, which can help identify regional trends in fraudulent activity.
- **payee_location**: Geographic location of the payee, useful for analyzing patterns in transactions between different regions.
- **beneficiary_mcc_code**: Merchant category code (MCC) representing the type of business of the payee, valuable for identifying high-risk categories.
- **remitter_mcc_code**: Merchant category code representing the type of business of the remitter, which can be analyzed for fraud patterns.
- **dt_time_txn_compl**: Date and time when the transaction was completed, crucial for time-based analysis of fraudulent activities.
- **time_of_day**: Time of day when the transaction occurred, often categorized into intervals (e.g., morning, evening), useful for spotting trends.
- **error_description**: Descriptive text providing details about the error (if applicable), aiding in understanding common issues that arise.

## Technologies Used
- Python
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
  - Plotly
- Jupyter Notebook

## Visualizations
The project includes various visualizations to analyze transaction data, including:
- Distribution of transaction types involved in fraud.
- Boxplots comparing requested and settlement amounts by transaction status.
- Time series analysis of fraud transactions over months.
- Heatmaps of correlations between numeric variables.

## Analysis
The analysis provides insights into:

- Transaction trends over time and by geographical location.
- Error codes associated with fraudulent transactions.
- Comparisons between payer and payee states regarding transaction statuses.
