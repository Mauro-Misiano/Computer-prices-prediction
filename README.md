# Computer-prices-prediction

This project leverages Machine Learning techniques to predict computer prices based on their features. The model was developed using PyCaret, a library that automates common Machine Learning workflows, and is optimized to identify the most relevant features in the dataset.

🚀 Project Objective

To build a predictive model that estimates the price of computers in US dollars (USD) using information such as memory type, storage capacity, processor, and other key characteristics.

📂 Project Structure

notebooks/: Contains the main notebook with the model development.

data/: Folder with the original dataset and transformed data.

src/: Source code and helper functions for preprocessing and evaluation.

outputs/: Results, visualizations, and metrics generated during the analysis.


🔧 Technologies and Tools Used

Libraries: pandas, numpy, matplotlib, seaborn, pycaret, ydata_profiling

Jupyter Notebook

PyCaret for automated model selection and tuning.


📈 Analysis Workflow

1. Data Loading and Exploration
The dataset includes prices in Indian Rupees, which were converted to US Dollars using the average 2023 exchange rate.
Features like memory type and storage capacity were also processed for clarity.


2. Data Cleaning and Transformation
Outliers were removed, numerical variables were normalized, and new, more representative columns were created.


3. Model Training
Multiple models were compared using PyCaret's compare_models() function, selecting the best one based on metrics like MAE, RMSE, and R2.


4. Results Visualization
Visualizations were created to interpret feature importance and evaluate the performance of the final model.
