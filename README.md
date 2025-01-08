# NHL-Player-Salary-Prediction

## 📋 Project Overview
This project predicts the salaries of athletes based on various features, such as performance metrics, demographics, and team statistics. The goal is to leverage machine learning techniques to identify key factors influencing athlete salaries and provide accurate predictions.

## 🎯 Objectives
- Analyze patterns and trends in athlete salary data.
- Build and evaluate a machine learning model to predict salaries.
- Provide insights into the most influential features affecting salaries.

## 🔂 Dataset
- **Source**: [Predict NHL Player Salaries](https://www.kaggle.com/datasets/camnugent/predict-nhl-player-salaries?fbclid=IwZXh0bgNhZW0CMTEAAR2gJARo0hYfDDEzCHjBdIZt9uHmnHwM0VNbsXLsSl0OaqajnTXrnDlxjMw_aem_hPB9Hpt42oUJLNQvzbea_Q)
- **Description**: Includes data on athlete demographics, performance metrics, team information, and salaries.
- **Preprocessing**: The data cleaning process involves filling or dropping missing values, removing duplicates, standardizing data formats, handling outliers using statistical methods, encoding categorical variables, and saving the cleaned dataset for analysis.

## 🛠️ Methodology
1. **Data Exploration**: Performed exploratory data analysis (EDA) to understand trends and correlations.
2. **Feature Engineering**: Key features created or transformed include aggregated performance scores, experience levels, team strength metrics, position encodings, and normalization.
3. **Model Selection**: Tested multiple models, including Linear Regression, Random Forest, Ridge and Lasso Regression, Decision Trees, etc.
4. **Evaluation**: Used metrics like Mean Absolute Error (MAE), Mean Squared Error (MSE), and R² to evaluate model performance.

## 🧙️‍♂️ Tools and Technologies
- **Programming Language**: Python
- **Libraries**: pandas, NumPy, scikit-learn, matplotlib, seaborn, etc.
- **Other Tools**: Google Colab, Excel.

## 🚀 How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/margiecaina/NHL-Player-Salary-Prediction/
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the notebook or script:
   ```bash
   python salary_prediction.py
   ```
