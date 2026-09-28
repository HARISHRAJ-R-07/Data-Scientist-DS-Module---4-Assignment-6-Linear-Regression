📱 Mobile Price Prediction using Linear Regression

A beginner-friendly Machine Learning project to predict mobile phone prices using Linear Regression.

📌 Project Overview

This project uses Linear Regression to predict mobile prices based on selected mobile specifications.

Selected Features:

🧠 RAM
🔋 Battery
📸 Front Camera
⚙️ CPU Core

Target Variable:

💰 Mobile Price

🎯 Objective

The main objective of this project is to understand how mobile specifications are related to price and build a Linear Regression model to predict mobile prices.

🛠️ Technologies Used

🐍 Python
🐼 Pandas
🔢 NumPy
📊 Matplotlib
📈 Seaborn
🤖 Scikit-learn
💻 Google Colab / Jupyter Notebook

🔄 Project Workflow

Dataset
↓
Data Cleaning & Preparation
↓
Correlation Analysis
↓
Feature Selection
↓
Train-Test Split
↓
Linear Regression
↓
Prediction
↓
Model Evaluation

📊 Model Results

R² Score: 0.8739
Mean Absolute Error (MAE): 216.01
Mean Squared Error (MSE): 77263.12
Intercept: 897.14

The R² score of 0.8739 means that the model explains about 87.39% of the variation in mobile prices.

📈 Feature Coefficients

RAM: 342.55
Battery: 0.017
Front Camera: 1.42
CPU Core: 105.69

The positive coefficients show that an increase in these features is associated with an increase in the predicted mobile price, while keeping the other features constant.

📉 Feature Analysis

The plots folder contains scatter plots showing the relationship between the selected features and mobile price.

🧠 RAM vs Mobile Price
🔋 Battery vs Mobile Price
📸 Front Camera vs Mobile Price
⚙️ CPU Core vs Mobile Price

📁 Project Structure

Mobile-Price-Linear-Regression/

├── Linear_Regression.ipynb
├── README.md
├── requirements.txt
└── plots/
├── RAM_vs_Price.png
├── Battery_vs_Price.png
├── Front_Cam_vs_Price.png
└── CPU_Core_vs_Price.png

💡 Key Insights

The correlation analysis and scatter plots helped identify useful relationships between mobile specifications and price.

RAM, battery, front camera, and CPU core were selected as the main features for the Linear Regression model.

The model gives reasonably good predictions, but additional features and other regression algorithms can be tested for further improvement.

🚀 Future Improvements

➕ Add more relevant mobile features.
🧹 Improve data preprocessing.
📊 Handle outliers more effectively.
🤖 Compare Linear Regression with Random Forest and other regression models.
🔄 Use cross-validation for more reliable evaluation.
⚙️ Perform additional feature engineering.

👨‍💻 Author

Harishraj R

🎓 B.Sc. Computer Science and Data Science

⭐ If you find this project useful, feel free to explore the notebook!
