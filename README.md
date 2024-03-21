# Laptop Price Predictor

**Project Overview:**
The Laptop Price Predictor project aims to predict the price of laptops based on various features such as processor type, RAM size, screen size, etc. The project follows a systematic approach starting from Exploratory Data Analysis (EDA) of the dataset followed by the application of multiple machine learning algorithms to find the best model for predicting laptop prices.

**Dataset EDA:**
The first phase of the project involved Exploratory Data Analysis (EDA) of the dataset. This step included:
- Understanding the structure and features of the dataset.
- Handling missing values, if any.
- Analyzing the distribution of features.
- Identifying correlations between features and the target variable (price).
- Visualizing data through various plots and graphs to gain insights.

**Machine Learning Models:**
After completing the EDA phase, several machine learning models were applied to predict laptop prices:
1. Linear Regression
2. Ridge Regression
3. Lasso Regression
4. K-Nearest Neighbors (KNN)
5. Decision Tree
6. Support Vector Machine (SVM)
7. Random Forest
8. Gradient Boosting
9. XGBoost

**Evaluation Metrics:**
The performance of each model was evaluated using the following metrics:
- **R-squared (R2) Score:** Indicates the proportion of the variance in the dependent variable that is predictable from the independent variables.
- **Mean Absolute Error (MAE):** Represents the average of the absolute errors between the predicted and actual values.

**Best Performing Model:**
Among all the models applied, **XGBoost** emerged as the best-performing model with the following evaluation metrics:
- **R2 Score:** 0.8811773435850243
- **MAE:** 0.16496203512600974

**Files Included:**
1. `dataset.csv`: Dataset containing laptop features and prices.
2. `Laptop_Price_Predictor.ipynb`: Jupyter Notebook containing the code for EDA and model implementation.
3. `requirements.txt`: List of Python libraries required to run the code.

**Instructions for Running the Code:**
1. Ensure Python and Jupyter Notebook are installed on your system.
2. Clone the repository to your local machine.
3. Install the required libraries using `pip install -r requirements.txt`.
4. Open `Laptop_Price_Predictor.ipynb` in Jupyter Notebook.
5. Follow the instructions in the notebook to execute the code cells.

**Conclusion:**
The Laptop Price Predictor project demonstrates the application of exploratory data analysis and various machine learning algorithms to predict laptop prices accurately. XGBoost, with its high R2 score and low MAE, proves to be the most suitable model for this prediction task. This project can be further enhanced by incorporating additional features or experimenting with different algorithms to improve prediction accuracy further.
