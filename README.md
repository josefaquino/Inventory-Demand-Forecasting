# Sales Forecasting and Inventory Optimization with Machine Learning

## Project Overview

This project demonstrates the application of machine learning techniques to forecast product demand and optimize inventory management in a retail/eCommerce context. Using synthetic data simulating 20 SKUs over 6 months, the project highlights how to build time series forecasting models and extract actionable business insights.

The forecasting model employs Facebook Prophet to capture demand seasonality and trends, generating future sales predictions. It also identifies SKUs at risk of stockouts and those with high demand variability to support safety stock calculations and purchasing decisions.

## Features

- Synthetic sales data generation with seasonality, noise, and simulated stockouts
- Demand forecasting using Prophet time series model
- Visualization of forecast results and seasonal components
- Identification of stockout risks and demand variability per SKU
- Easily extendable for real datasets and integration into inventory systems

## Getting Started

### Requirements

- Python 3.8+
- pandas
- numpy
- matplotlib
- prophet
- (optional) Google Colab for notebook execution and visualization

### Running the Project

1. Clone the repository:


## Getting Started

### Requirements

- Python 3.8+
- pandas
- numpy
- matplotlib
- prophet
- (optional) Google Colab for notebook execution and visualization

### Running the Project

1. Clone the repository:
git clone https://github.com/josefaquino/your-repo-name.git
cd your-repo-name


2. Install dependencies:
pip install pandas numpy matplotlib prophet



3. Run the Jupyter/Colab notebook to generate synthetic data, train the model, and visualize results.

## Project Structure

- `synthetic_sales_data.csv` — generated synthetic dataset
- `forecasting_notebook.ipynb` — example notebook with data generation, modeling, and insights extraction
- `README.md` — project documentation

## Strategic Insights from Analysis

The following tables highlight key SKUs identified from the synthetic dataset based on their risk of stockout (measured by days with zero sales) and demand variability (standard deviation of sales). These KPIs can guide inventory safety stock policies and purchasing priorities.

### Top SKUs with Risk of Stockout (Most Zero Sales Days)

| SKU    | Zero Sales Days |
|--------|-----------------|
| SKU_3  | 18              |
| SKU_11 | 15              |
| SKU_7  | 14              |
| SKU_6  | 13              |
| SKU_1  | 12              |

### Top SKUs with Highest Demand Variability

| SKU     | Demand Variability (Std. Dev.) |
|---------|-------------------------------|
| SKU_11  | 50.074841                     |
| SKU_10  | 47.956108                     |
| SKU_14  | 40.539771                     |
| SKU_1   | 40.360021                     |
| SKU_4   | 40.136372                     |

*Note: Data is synthetically generated for demonstration purposes and can be adapted to real datasets.*

## Author

Jose Araújo  
GitHub: [https://github.com/josefaquino](https://github.com/josefaquino)  
Date: 25/09/2025

## License

This project is licensed under the MIT License.

