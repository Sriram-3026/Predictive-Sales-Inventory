Predictive Sales & Inventory Optimization
This project focuses on forecasting retail sales trends and optimizing inventory management using Machine Learning. By analyzing historical sales data, the model predicts future demand and calculates key inventory metrics like Safety Stock and Reorder Points (ROP).

✨ Key Features
Sales Forecasting: Predicts future sales using the RandomForestRegressor algorithm.
Inventory Metrics: Automatically calculates Safety Stock and Reorder Point (ROP) to prevent stock-outs.
Data Visualization: Provides insights through sales trend lines and correlation scatter plots.
Item-wise Analysis: Detailed optimization for high-demand products like Handbags, Tunics, etc.

🛠️ Tech Stack
Language: Python
Libraries: Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
Tool: Google Colab / Jupyter Notebook

📊 Project Workflow
Data Cleaning: Handled missing values and standardized date formats.
Exploratory Data Analysis (EDA): Visualized sales clusters and identified outliers in purchase amounts.
Model Training: Trained a Random Forest model on daily aggregated sales data.
Optimization: Applied inventory formulas to trigger restock alerts based on lead time and safety buffers.

📈 Results
Model Accuracy: Achieved a Mean Absolute Error (MAE) of 2.98.
Efficiency: Successfully automated the reordering trigger, ensuring optimal stock availability.

📁 Dataset
The project uses the Fashion_Retail_Sales.csv dataset, which includes transaction details, item categories, and customer ratings.
