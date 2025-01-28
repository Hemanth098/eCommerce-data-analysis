# E-commerce Customer Insights and Lookalike Modeling

This repository contains a comprehensive data science solution for analyzing e-commerce customer data. It addresses three main tasks:

1. Exploratory Data Analysis (EDA)
2. Lookalike Modeling
3. Customer Segmentation

This code provides valuable insights into customer behavior, product performance, and sales trends, enabling you to make informed marketing decisions.

## Project Structure

The repository is organized into the following folders:

* `data`: Contains the raw CSV files (`Customers.csv`, `Products.csv`, and `Transactions.csv`).
* `src`: Contains the Python scripts for each analysis step:
    * `eda.py`: Performs Exploratory Data Analysis.
    * `lookalike_modeling.py`: Builds and applies a Lookalike Model.
    * `customer_segmentation.py`: Segments customers using K-Means clustering.
* `output`: Stores the generated output files:
    * `Lookalike.csv`: Contains lookalike customer recommendations for each customer.
    * `eda_plots` (folder): Contains visualizations generated during EDA.

## Dependencies

This code requires the following Python libraries:

* pandas
* numpy
* matplotlib
* scikit-learn
* datetime

## Running the Code

1. Clone this repository.
2. Install the required libraries:

```bash
pip install pandas numpy matplotlib scikit-learn datetime
