# Inventory Demand Prediction and Optimization using XGBoost

## Overview
This project leverages XGBoost to predict product demand based on historical sales data and product attributes. The goal is to forecast demand and optimize inventory management by calculating the optimal reorder points, ensuring products are stocked efficiently.

## Features
- **Data Preprocessing**: Handles missing values, creates new features like 'ProductAge' and 'PriceSensitivity'.
- **Modeling**: Uses XGBoost to predict product demand ('SoldFlag') and evaluates the model with RMSE and R² scores.
- **Evaluation**: Visualizes actual vs predicted demand, residuals, and feature importance.
- **Optimization**: Computes the optimal reorder point using a safety stock strategy based on predicted demand.

## Installation
To run the project, make sure you have Python installed along with the required libraries. You can install the necessary dependencies using pip:

```bash
pip install -r requirements.txt
Usage
Clone the repository:
bash
Copy code
git clone https://github.com/CipherNomad/inventory-demand-prediction.git
Navigate to the project directory:
bash
Copy code
cd inventory-demand-prediction
Run the script:
bash
Copy code
python demand_optimization.py
This will train the XGBoost model, predict demand, and calculate the optimal inventory levels, which will be saved in a CSV file.

Data
The dataset used for this project (SalesKaggle3.csv) contains information such as:

Product release number
Price sensitivity
Item count
Sales data
Ensure the dataset is placed in the same directory as the script or update the path in the code.

Results
The model's predictions and optimal inventory levels are saved in OptimalInventoryLevels.csv. This file includes the predicted demand, safety stock, and optimal reorder points for each product SKU.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
XGBoost: For providing a powerful and efficient machine learning model.
Matplotlib and Scikit-learn: For visualization and model evaluation.
markdown
Copy code

### Steps to add this to your GitHub repo:
1. Go to your GitHub repository at [CipherNomad](https://github.com/CipherNomad).
2. Click on "Add file" -> "Create new file".
3. Name the file `README.md`.
4. Paste the above content into the file.
5. Commit the new file to save it.

This will ensure that the updated README content appears in your GitHub repository.





