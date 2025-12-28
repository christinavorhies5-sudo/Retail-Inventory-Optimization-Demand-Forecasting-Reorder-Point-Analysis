# Retail-Inventory-Optimization-Demand-Forecasting-Reorder-Point-Analysis
"An end-to-end data science project optimizing retail inventory through demand forecasting and reorder point analysis. Features time-series modeling with Facebook Prophet, automated safety stock logic, and interactive visualizations to prevent stockouts and reduce overstock.


# Retail Inventory Optimization: Demand Forecasting & Reorder Point Analysis

"An end-to-end data science project optimizing retail inventory through demand forecasting and reorder point analysis. Features time-series modeling with Facebook Prophet, automated safety stock logic, and interactive visualizations to prevent stockouts and reduce overstock."

## 🚀 Project Overview
This project provides a comprehensive framework for **Retail Inventory Optimization** by combining advanced time-series forecasting with automated supply chain logic. By leveraging retail datasets, the analysis identifies critical demand patterns and operational risks.

## 🛠️ Key Features
* **Predictive Modeling**: Utilized **Facebook Prophet** to forecast daily units sold for a 90-day period.
* **Advanced Feature Engineering**: Improved accuracy by incorporating **US Holiday effects** and seasonal decomposition.
* **Automated Reorder Logic**: Developed a robust calculation for **Reorder Points** using 95% confidence intervals.
* **Portfolio Scalability**: Scaled analysis across a 20-product portfolio to generate a comprehensive **Final Inventory Reorder Report**.

## 📊 Business Impact
* **Prevents Stockouts**: Ensures stock is available during replenishment windows using 7-day lead times.
* **Reduces Overstock**: Minimizes capital tied up in slow-moving inventory by aligning orders with forecasted demand.
* **Data-Driven Decisions**: Provides a scalable solution ready for export to Tableau or Power BI.

## 📂 Project Structure
* `retail_inventory_analysis.ipynb`: Full analysis and visualization code.
* `requirements.txt`: List of necessary Python libraries.
* `data/`: Directory for raw and processed datasets.

## 💻 How to Run
1. Clone the repository.
2. Install dependencies: `pip install pandas plotly duckdb prophet`.
3. Open the notebook in Jupyter or Google Colab to view the full analysis.
