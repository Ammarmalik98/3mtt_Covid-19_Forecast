# COVID-19 Time-Series Forecasting Project  

This repository contains a comprehensive analysis and time-series forecasting project based on COVID-19 data. The goal of this project is to uncover trends, analyze demographic data, visualize findings, and build predictive models to forecast future trends.

## Features  
- **Data Preprocessing:**  
  - Handling missing and duplicate values.  
  - Calculating Mortality and Recovery Rates.  
  - Aggregating and scaling data for model training.  

- **Exploratory Data Analysis (EDA):**  
  - Visualizing top and bottom 10 countries/regions by cases.  
  - Analyzing trends based on WHO regions.  
  - Correlation analysis to identify key relationships.  

- **Time-Series Forecasting:**  
  - Built using SARIMA.  
  - Forecasted trends for 'Confirmed', 'Deaths', 'Recovered', and 'Active' cases.  
  - Achieved accuracy improvements after data preprocessing.  

## Dataset  
- **Source:** [Kaggle - COVID-19 Dataset](https://www.kaggle.com/datasets/imdevskp/corona-virus-report)  
- **Description:** Contains global COVID-19 case counts and demographics.  

## Tools & Libraries  
- **Programming Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Statsmodels  
- **Environment:** Jupyter Notebook  

## Project Structure  
```
📂 COVID-19_Time-Series_Forecasting  
├── 📁 data  
│   └── covid19_dataset.csv  
├── 📁 notebooks  
│   └── analysis_and_forecasting.ipynb  
├── 📁 visuals  
│   └── visualizations.png  
├── 📄 README.md  
└── 📄 requirements.txt  
```

## Key Results  
- Improved forecasting accuracy after scaling and aggregation.  
- Achieved MSE: 0.20, MAE: 0.45, RMSE: 0.45 on 'Confirmed' Cases.  
- Consistent accuracy for other categories ('Deaths', 'Recovered', 'Active').  

## How to Use  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/your-username/covid19-forecasting.git  
   ```  
2. Install the required libraries:  
   ```bash  
   pip install -r requirements.txt  
   ```  
3. Open the Jupyter Notebook to explore the analysis and run the forecasting models.  

## Future Improvements  
- Explore alternative models like LSTMs for enhanced performance.  
- Integrate external data (e.g., vaccination rates, mobility data).  
- Automate the process to fetch and update data in real-time.  

## Acknowledgments  
- Dataset by Kaggle community ([source link](https://www.kaggle.com/datasets/imdevskp/corona-virus-report)).  
- Python community for the robust ecosystem of libraries.  

