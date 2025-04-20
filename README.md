# Property Prediction Model

*Predict house prices in Bengaluru based on property attributes using machine learning regression techniques and thorough exploratory analysis*.

---

## Project Overview

Real_Estate_Price_Prediction aims to develop a predictive model for house prices in Bengaluru, India, by leveraging historical real estate data and applying regression algorithms.

---

## Data Story

### Aim & Goal

- **Aim**: Build an accurate model to predict real estate prices in Bengaluru.

- **Goal**: Identify key factors influencing price and optimize model performance using feature engineering and hyperparameter tuning.

### Problem Statement

Rapidly changing real estate markets make pricing predictions challenging. Stakeholders need reliable models to estimate property values based on features like location, size, and amenities.

### Our Approach

1. **Data Ingestion & Cleaning**:

- Load Bengaluru_House_Data.csv.

- Handle missing values, encode categorical variables, and normalize numerical features.

2. **Exploratory Data Analysis (EDA)**:

- Visualize distributions of price, size (sqft), and location frequency.

- Identify outliers and correlations among features.

3. **Feature Engineering**:

- Create new features (e.g., price per sqft, total area categories).

- Perform one-hot encoding for location and other categorical fields.

4. **Model Training & Tuning**:

- Split data into train/test sets.

- Train regression models: Linear Regression, Lasso, Ridge, ElasticNet, Gradient Boosting.

- Use GridSearchCV with ShuffleSplit for hyperparameter optimization.

5. **Evaluation & Insights**:

- Compare model performance using cross-validation RMSE.

- Analyze feature importances and prediction errors.


### Key Skills & Technologies

1. **Languages & Libraries**: Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

2. **Techniques**: Data Cleaning, EDA, Feature Engineering, Regression Modeling, Hyperparameter Tuning


### Project Setup

#### Prerequisites

- Python 3.7 or higher

- Jupyter Notebook

- Pandas

- NumPy

- Matplotlib

- Seaborn

- Scikit-learn

### Installation & Usage

1. **Clone the Repository:**
   ```bash
    git clone https://github.com/yourusername/Real_Estate_Price_Prediction.git
    cd Real_Estate_Price_Prediction

2. **Data File**
Place Bengaluru_House_Data.csv in the project root.

3. **Install Dependencies**
    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn jupyter

4. **Run the Notebook**
    
jupyter notebook "Real_estate_Price_Prediction.ipynb"


### License

This project is licensed under the MIT License.

### Data Source Credit

Data sourced from Kaggle: Bengaluru House Data

### Contributors

## Asad Khan





