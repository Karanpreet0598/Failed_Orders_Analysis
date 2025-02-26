# Failed Orders Analysis

## Overview

This repository contains an assignment focused on data analysis using Python. The project involves analyzing orders and offers data to derive insights. The study is performed in a Jupyter Notebook (code.ipynb).

## Dataset

The analysis is based on the following datasets:

data_offers.csv: Contains information about various offers and promotions.

data_orders.csv: Contains details of customer orders.

## Requirements

Ensure you have the following installed:

- Python 3.x

- Jupyter Notebook

- Pandas

- NumPy

- Matplotlib / Seaborn (for visualization)

You can install the required dependencies using:

> pip install pandas numpy matplotlib seaborn

## Usage

Clone this repository:

> git clone https://github.com/Karanpreet0598/Failed_Orders_Analysis
>
>>cd Failed_Orders_Analysis

Open the Jupyter Notebook: code.ipynb

Run the cells sequentially to perform the analysis.

Project Structure

| File/Folder         | Description                              |
|---------------------|------------------------------------------|
| `code.ipynb`       | Jupyter Notebook with analysis          |
| `data_offers.csv`  | Offers dataset                          |
| `data_orders.csv`  | Orders dataset                          |
| `charts/`          | Folder containing generated charts      |
| `README.md`        | Project documentation                   |


## Analysis Overview

The analysis performed in the notebook includes:

Data Cleaning: Handling missing values, standardizing formats, and removing duplicates.

Exploratory Data Analysis (EDA): Understanding data distribution, relationships, and key statistics.

Offer Performance Analysis: Identifying the most effective offers based on conversion rates.

Order Trends: Analyzing sales patterns, peak order times, and customer purchasing behavior.

Visualization: Using charts and graphs to represent key findings.

Results & Insights

Top Performing Offers: Identified the offers with the highest redemption rates.

Customer Purchase Patterns: Analyzed how users interact with offers and their buying frequency.

Sales Trends: Visualized monthly and seasonal sales variations.

Order Value Distribution: Explored the distribution of order values to identify common spending patterns.

Charts & Graphs:

![Orders according to reasons for failure](/images/heatmap_by_order_status.png)


![Cancelled orders by hour](/Images/cancelled_orders_by_hour.png)


![Cancelled orders by hour and Driver Status](/Images/time_of_cancelled_orders_by_time_hour.png)


![Average ETA by hour of day](/Images/ETA_by_hour_of_day.png)


**Contributing**

Feel free to fork the repository, make enhancements, and submit pull requests.

License

***This project is open-source and free to use. Modify as needed!***
