# Predicting Company's Cash Flow for Upcoming Years

## Project Overview
This project aims to develop a predictive model that accurately forecasts a company's cash flow for the next year, using historical financial data. By leveraging machine learning techniques on extensive financial datasets, our goal is to provide valuable insights into the company's financial health and future performance, aiding investors, financial analysts, and stakeholders in making informed decisions.

### Objectives
- To predict a company's cash flow for the upcoming year based on its historical balance sheet financials and income statement datasets.
- To assist in financial planning, investment decisions, and risk management by providing accurate forecasts of cash flow.
- To leverage machine learning techniques to identify patterns and relationships within financial data.

## Datasets Description
Our analysis focuses on The Walt Disney Company, utilizing quarterly financial datasets spanning from 09/30/1985 to 12/31/2023. These datasets include:
- **Balance Sheet Dataset (`DIS_quarterly_balance-sheet.csv`):** Comprehensive quarterly balance sheet details, including assets, liabilities, and equity.
- **Cash Flow Statement Dataset (`DIS_quarterly_cash-flow.csv`):** Detailed quarterly information on cash flow from operating, investing, and financing activities.
- **General Financials Dataset (`DIS_quarterly_financials.csv`):** A broad overview of the company's quarterly financial performance, including revenue, cost of revenue, and operating expenses.

## Methodology and Plan
The project follows a structured approach encompassing data collection and preprocessing, feature engineering, model selection, training, evaluation, and deployment. Key steps include:
- **Data Collection and Preprocessing:** Gathering and preprocessing 30 years of The Walt Disney Company's historical financial data.
- **Feature Engineering:** Identifying relevant features such as liquidity ratios, profitability metrics, and leverage ratios.
- **Model Selection:** Experimenting with machine learning algorithms suitable for time series forecasting, including ARIMA, LSTM, and XGBoost.
- **Model Training and Evaluation:** Training models on historical data and evaluating their performance using metrics like MAE or RMSE.
- **Hyperparameter Tuning and Deployment:** Optimizing model performance and deploying the model for user access or integration into financial analysis tools.

## Schedule
- **Data Preprocessing and Feature Engineering:** 2 weeks
- **Model Training and Evaluation:** 3 weeks
- **Hyperparameter Tuning:** 1 week
- **Forecasting and Analysis:** 1 week
- **Documentation:** 1 week

## Resources Needed
- Historical financial datasets of The Walt Disney Company.
- Machine learning libraries and tools (Python, TensorFlow, Sci-kit-learn).
- Access to relevant financial forecasting and machine learning research papers and literature.
