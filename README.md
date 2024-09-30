# UK Housing Expenditure Prediction Using Macroeconomic Indicators

## 📄 Project Overview

This project explores housing costs and household expenditures in the UK from 2002 to 2022, using machine learning models such as **K-Nearest Neighbors (KNN)**, **Linear Regression**, and **SARIMA**. The goal is to predict household expenditures on goods and services for routine maintenance based on macroeconomic factors like rental prices and housing costs.

This project supports business decisions related to resource allocation, pricing strategies, and budgeting for companies in real estate, household maintenance, and finance sectors.

## 🚀 Key Features

- **Data Processing**: Cleaning and merging datasets from multiple sources (UK Housing Market and Consumer Trends).
- **Predictive Models**:
  - **KNN** for non-linear relationships between rental prices and household expenditure.
  - **Linear Regression** for a simpler, interpretable model.
  - **SARIMA** for time-series forecasting of expenditures.
- **Data Storage**: The processed data and model performance results are designed to be stored in an SQLite database.
- **Business Impact**: The analysis provides insights into how housing costs influence household expenditure, helping businesses in strategic planning.

## 🛠️ Technologies Used

- **Programming Languages**: Python
- **Libraries**: Pandas, NumPy, Scikit-learn, Matplotlib, Statsmodels
- **Database**: SQLite (not required to run)

## 📊 Data Sources

1. **UK Housing Market and Economic Indicators** (synthetic dataset from [Kaggle](https://www.kaggle.com/datasets/rahuljangir78/uk-housing-market-and-economic-indicators))  
   A synthetic dataset mimicking realistic patterns and trends in the UK housing market and economy.
2. **UK Consumer Trends Dataset** (from the [Office for National Statistics (ONS)](https://www.kaggle.com/datasets/matarrgaye/uk-consumer-trends-current-price))  
   This dataset contains quarterly data on consumer expenditures across various categories from 1997 to 2022.

## 🔍 Project Structure

- **/data**: Contains raw and cleaned datasets used in the analysis.
- **/notebooks**: Contains the Jupyter notebook with all analysis and modeling.
- **/scripts**: Python scripts for data cleaning, model training, and evaluation.
- **/visualizations**: Plots and graphs generated during exploratory data analysis and model evaluation.
- **/models**: Trained models saved in `pickle` format.

## 📈 Results and Findings

The models were trained on the historical UK housing and expenditure data and evaluated based on their predictive performance.

- **KNN Model** achieved an R² score of **0.928**, indicating a strong relationship between rental prices and household expenditure on goods and services.
- **Linear Regression** had an R² score of **0.83**, which was slightly lower than KNN.
- **SARIMA** model forecasted rental prices and household expenditures for the next two years, capturing seasonal trends effectively.

### Key Insight:

- Rental prices are a strong indicator of household expenditure trends. This information can be used by businesses in sectors like real estate and home maintenance to better plan for future market conditions.

## 🏆 Business Applications

- **Strategic Planning**: Anticipating consumer spending patterns to adjust business strategies.
- **Budgeting and Resource Allocation**: Assisting businesses in real estate and household maintenance to better allocate resources.
- **Pricing Strategy**: Allowing retailers to adjust prices based on seasonal trends in household expenditure.

## 📋 Installation and Usage (Optional)

You can explore the code by running the Jupyter notebook:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/UK_Housing_Expenditure_Prediction.git
   cd UK_Housing_Expenditure_Prediction
   ```
2. Install dependencies:
   pip install -r requirements.txt

3. Run the notebook:
   jupyter notebook notebooks/prediction_model.ipynb

- Note: Running the SQLite database is optional and not required for understanding the project or results.

## 📝 License

This project is licensed under the MIT License - see the LICENSE.md file for details.

- **Data Usage Disclaimer**: This project uses two datasets: one synthetic and one real. The synthetic dataset comes from Kaggle, and the UK Consumer Trends dataset is sourced from the Office for National Statistics (ONS). Please ensure proper attribution when using these datasets for further research or projects.

## 👨‍💻 Author

Mehrdad Atariani
[LinkedIn][def]

[def]: https://www.linkedin.com/in/mehrdad-atariani/
