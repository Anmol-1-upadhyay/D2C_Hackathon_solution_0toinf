# Predictive Analytics for Inventory Management and Demand Forecasting

## Overview
This project, developed for the D2C Hackathon, focuses on leveraging predictive analytics to optimize inventory management and demand forecasting. The solution employs advanced time-series forecasting models to provide actionable insights that enhance decision-making in supply chain management.

## Objective
The primary goal is to forecast demand for the upcoming month using state-of-the-art machine learning and deep learning models. This helps businesses optimize inventory levels, reduce wastage, and improve overall supply chain efficiency.

## Models Used
1. **MSTL (Multiple Seasonal-Trend Decomposition using Loess)**
   - A robust decomposition-based model that captures multiple seasonal patterns and trends in time-series data.
   - Useful for handling complex seasonality and trend components.

2. **TimeGPT**
   - A generative AI-powered forecasting model designed to handle time-series data efficiently.
   - Provides highly accurate predictions with minimal parameter tuning.

## Key Features
- **Automated Data Preprocessing**: Cleans and prepares raw inventory and sales data for model training.
- **Demand Forecasting**: Generates monthly demand predictions to optimize inventory levels.
- **Visualization & Insights**: Offers interactive charts and dashboards to understand demand trends.
- **Scalability**: Can be extended to handle multi-location and multi-product forecasting.

## Technology Stack
- **Python** (Pandas, NumPy, Scikit-learn, Statsmodels)
- **Time-Series Libraries** (MSTL, TimeGPT)
- **Visualization Tools** (Matplotlib, Seaborn, Plotly)
- **Jupyter Notebook** for experimentation and model training

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/your-repo/D2C_Hackathon_solution_0toinf.git
   ```
2. Navigate to the project directory:
   ```sh
   cd D2C_Hackathon_solution_0toinf
   ```
3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## Usage
1. Prepare your dataset in CSV format with columns such as `Date`, `Product_ID`, `Sales_Quantity`.
2. Run the preprocessing script:
   ```sh
   python preprocess.py
   ```
3. Train the forecasting model:
   ```sh
   python train_model.py --model MSTL
   ```
   or
   ```sh
   python train_model.py --model TimeGPT
   ```
4. Generate demand forecasts:
   ```sh
   python forecast.py --month YYYY-MM
   ```
5. Visualize results using the dashboard:
   ```sh
   streamlit run dashboard.py
   ```

## Contributors
- **Anmol** (Lead ML Engineer)
- **Team 0toinf**

## License
This project is licensed under the MIT Open License.

