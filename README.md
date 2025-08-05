# 🚗 Analyzing Selling Price of Used Cars using Python

This project focuses on exploring and analyzing a dataset of used cars to understand the factors influencing their selling price. Using Python, we perform data cleaning, exploratory data analysis (EDA), feature engineering, and predictive modeling to build insights and potentially guide pricing strategies.

## 📂 Project Structure

```
├── Analyzing_Selling_Price_of_used_Cars_using_Python.ipynb
├── README.md
├── data/
│   └── used_cars.csv
├── images/
│   └── plots, charts, and visualizations
└── models/
    └── trained_model.pkl (optional)
```

## 📌 Objectives

- Understand which features impact the selling price of used cars.
- Clean and preprocess the dataset.
- Perform EDA using visualizations.
- Train regression models to predict car prices.
- Evaluate model performance.

## 🛠️ Technologies & Libraries Used

- **Python**
- **Pandas** – data manipulation
- **NumPy** – numerical computing
- **Matplotlib & Seaborn** – data visualization
- **Scikit-learn** – model building and evaluation
- **Jupyter Notebook** – development environment

## 📊 Key Steps Performed

1. **Data Cleaning**  
   - Handled missing values  
   - Converted categorical variables  
   - Dropped irrelevant features

2. **Exploratory Data Analysis (EDA)**  
   - Visualized distribution of features  
   - Correlation analysis  
   - Scatter plots between predictors and selling price

3. **Feature Engineering**  
   - Derived new features like car age  
   - One-hot encoding for categorical variables

4. **Model Building**  
   - Linear Regression  
   - Random Forest Regressor  
   - Model tuning and comparison

5. **Model Evaluation**  
   - Used RMSE and R² metrics  
   - Evaluated feature importance

## 📈 Results & Insights

- Older vehicles tend to sell for less.
- Fuel type, seller type, and car condition significantly affect pricing.
- Random Forest performed better than Linear Regression in prediction accuracy.

## 🚀 How to Run

1. Clone this repository.
2. Install dependencies using:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the notebook:
   ```bash
   jupyter notebook Analyzing_Selling_Price_of_used_Cars_using_Python.ipynb
   ```
4. Run all cells and explore the outputs.

## 🔮 Future Improvements

- Incorporate more advanced models like XGBoost.
- Deploy the model using Streamlit or Flask.
- Add model explainability using SHAP or LIME.

## 📁 Data Source

Used cars dataset sourced from [Kaggle / internal source].  
*(Note: Include the actual data source link if publicly available.)*

## 🤝 Contribution

Feel free to fork, raise issues, or contribute enhancements via PR.

## 📬 Contact

**Author:** Garry Roque Fernandes  
**Email:** garryfernandes2@gmail.com  
**LinkedIn:** [LinkedIn Profile](https://linkedin.com/in/garryfernandes2)
