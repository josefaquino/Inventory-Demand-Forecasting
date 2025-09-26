Sales Forecasting and Inventory Optimization with Machine Learning
Project Overview
This project demonstrates the application of machine learning techniques to forecast product demand and optimize inventory management in a retail/eCommerce context. Using synthetic data simulating 20 SKUs over 6 months, the project highlights how to build time series forecasting models and extract actionable business insights.

The forecasting model employs Facebook Prophet to capture demand seasonality and trends, generating future sales predictions. It also identifies SKUs at risk of stockouts and those with high demand variability to support safety stock calculations and purchasing decisions.

Features
Synthetic sales data generation with seasonality, noise, and simulated stockouts

Demand forecasting using Prophet time series model

Visualization of forecast results and seasonal components

Identification of stockout risks and demand variability per SKU

Easily extendable for real datasets and integration into inventory systems

Getting Started
Requirements
Python 3.8+

pandas

numpy

matplotlib

prophet

(optional) Google Colab for notebook execution and visualization

Running the Project
Clone the repository:

text
git clone https://github.com/josefaquino/your-repo-name.git
cd your-repo-name
Install dependencies:

text
pip install pandas numpy matplotlib prophet
Run the Jupyter/Colab notebook to generate synthetic data, train the model, and visualize results.

Project Structure
synthetic_sales_data.csv — generated synthetic dataset

forecasting_notebook.ipynb — example notebook with data generation, modeling, and insights extraction

README.md — project documentation

Author
Jose Araújo
GitHub: https://github.com/josefaquino
Date: 25/09/2025

License
This project is licensed under the MIT License.
