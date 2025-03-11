# sales-prediction
Here, comparing actual sales and predicted sales
# 📈 Sales Prediction using Advertising Dataset

![Sales Prediction](https://d2eofpjy20wlpd.cloudfront.net/predict-big-mart-sales/images/BigMart_Sales_Prediction_Datasets.png)

## 📌 Overview
This project aims to predict **sales revenue** based on advertising expenditures using **Machine Learning** techniques. The dataset includes spending on different advertising channels (**TV, Radio, and Newspaper**) and their impact on sales.

## 🔥 Features
- **Exploratory Data Analysis (EDA)** to uncover trends and correlations.
- **Feature Engineering**: Handling missing values, scaling, and transformations.
- **Machine Learning Models** for sales prediction.
- **Model Evaluation**: R² Score, RMSE, and MAE.

## 📂 Dataset
The dataset used in this project is the **Advertising dataset** from [Kaggle](https://www.kaggle.com/datasets/ashydv/advertising-dataset).

**Columns in the dataset:**
- `TV`: Amount spent on TV advertising.
- `Radio`: Amount spent on Radio advertising.
- `Newspaper`: Amount spent on Newspaper advertising.
- `Sales`: Sales revenue generated.


## ⚙️ Installation
### 1️⃣ Clone the repository
```sh
git clone https://github.com/Ayesha-Siddiqua1/sales-prediction.git
cd sales-prediction
```
2️⃣ Install dependencies
Ensure you have Python installed, then install the required libraries:

```sh
Copy
Edit
pip install pandas numpy matplotlib seaborn scikit-learn
```

📊 Exploratory Data Analysis (EDA)
The project includes visualizations and statistical analysis to explore:

Correlation between ad spending and sales.
Feature importance.
Distribution of data.

🤖 Machine Learning Models
The project uses multiple ML models, including:

Linear Regression
Random Forest

I used Linear Regression ML model in the project. You can also Random Forest.

Model is evaluated using Mean Absolute Error (MAE), Mean Squared Error (MSE), and R² Score.

🚀 How to Run
Run the Python script to train the model and make predictions:
```
sh
Copy
Edit
python sales_prediction.py
```

📈 Results
Linear Regression achieved an R² score of ~90%, indicating strong correlation.

🌟 Star this repository if you found it useful!
