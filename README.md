# E-Commerce Sales & Analysis

This project focuses on analyzing and visualizing e-commerce sales data using Python and some of its most powerful libraries such as Pandas, NumPy, and Plotly. It provides insights into customer purchasing behavior, peak sales periods, city-wise revenue distribution, product trends, and more.

## Project Objectives

- Clean and preprocess raw sales data
- Perform exploratory data analysis (EDA)
- Identify monthly sales trends
- Analyze city-wise performance
- Discover best-selling products
- Find correlations between price and quantity sold
- Understand hourly sales patterns

## Technologies Used

- Python
- Pandas
- NumPy
- Plotly
- Jupyter Notebook

## Dataset

The dataset used in this project contains records of customer orders, including:
- Order ID
- Product
- Quantity Ordered
- Price Each
- Order Date
- Purchase Address

A sample dataset (`ecommerce_sales.csv`) is included with this repository.

## Features

1. **Data Cleaning**: Handling missing values, converting date formats, and creating new features like city and hour.
2. **Monthly Sales Analysis**: Identifying sales performance across different months.
3. **City-wise Revenue**: Ranking cities based on total sales.
4. **Top Products**: Identifying which products are sold the most.
5. **Price vs Quantity**: Visualizing the relationship between pricing and volume.
6. **Sales Trends by Hour**: Understanding when customers are most likely to place orders.

## Installation

1. Clone the repository:
git clone https://github.com/yourusername/ecommerce-sales-analysis.git cd ecommerce-sales-analysis


2. Create a virtual environment and activate it (optional but recommended):
python -m venv venv source venv/bin/activate # On Windows use venv\\Scripts\\activate

3. Install dependencies:
pip install pandas numpy plotly

4. Run the Jupyter Notebook:
jupyter notebook Ecommerce_Sales_Analysis.ipynb
## Usage

- Run the notebook cells step by step.
- Upload your own sales data or use the provided sample.
- Modify the visualizations or filters to tailor the analysis to your dataset.

## License

This project is open-source and available under the MIT License.

## Author

Created by Isha Bhama – feel free to reach out with suggestions or questions.
