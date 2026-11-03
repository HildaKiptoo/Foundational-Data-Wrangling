# Foundational Data Wrangling & Visualization in Python

## Overview
This project serves as a comprehensive, beginner-friendly introduction to data wrangling and visualization using Python. It was designed to demonstrate essential data manipulation techniques without relying on external `.csv` files. Instead, the notebook generates a synthetic, reproducible dataset of 1,000 student performance records—complete with intentionally injected missing values to simulate real-world data cleaning scenarios.

## Concepts Covered
This notebook guides you through the foundational steps of a data analytics workflow:
* **Data Creation:** Building DataFrames from NumPy arrays, dictionaries, and randomized synthetic generation.
* **Exploratory Data Analysis (EDA):** Inspecting dimensions, data types, and descriptive statistics.
* **Data Cleaning:** Identifying and imputing missing values (NaNs).
* **Feature Engineering:** Creating calculated columns (e.g., total scores) and conditional columns (e.g., pass/fail status) using `np.where`.
* **Filtering & Aggregation:** Subsetting data with boolean indexing, grouping data with `groupby()`, and building multi-dimensional Pivot Tables.
* **Data Visualization:** 
  * **Pandas/Matplotlib:** Histograms and Pie Charts.
  * **Seaborn:** Polished, static Box Plots for categorical comparisons.
  * **Plotly:** Interactive Scatter Plots with hover tools.

## Libraries Used
* `pandas` - Data manipulation and analysis
* `numpy` - Numerical computing and synthetic data generation
* `matplotlib` - Foundational plotting
* `seaborn` - Statistical data visualization
* `plotly` - Interactive graphing

## Setup and Installation
To run this notebook locally, ensure you have Python installed, along with Jupyter Notebook or an IDE like PyCharm/VS Code. 

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/Foundational-Data-Wrangling.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Foundational-Data-Wrangling
   ```
3. Install the required dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn plotly nbformat
   ```

## Usage
Open `StudentsPerformance_with_Plotly.ipynb` in your preferred Jupyter environment and run the cells sequentially. Because the dataset is generated at runtime with a fixed random seed (`np.random.seed(42)`), the results and visualizations will be identical every time you run it, making it a perfect reference guide for foundational Python skills.