# Car Price Prediction using Machine Learning

## Project Overview
This project aims to predict the selling price of used cars based on various features such as brand goodwill, horsepower, mileage, and more. We utilize regression models to estimate car prices, demonstrating practical machine learning applications in price prediction.

---

## Dataset
The dataset contains car-related features including:

- Brand / Manufacturer
- Horsepower
- Mileage
- Engine size
- Year of manufacture
- Transmission type
- And other relevant features

> **Note:** The dataset must be preprocessed by handling missing values and encoding categorical variables before training models.

---

## Workflow

1. **Data Loading and Exploration**
   - Load data using Pandas
   - Explore data using descriptive statistics and visualizations (histograms, scatter plots, heatmaps)

2. **Data Preprocessing**
   - Handle missing values
   - Encode categorical features (e.g., car brand)
   - Scale features if necessary

3. **Train-Test Split**
   - Split dataset into training and testing sets (typically 80/20 split)

4. **Model Training**
   - Train regression models including:
     - Linear Regression
     - Random Forest Regressor

5. **Model Evaluation**
   - Evaluate models using metrics such as:
     - Mean Squared Error (MSE)
     - Root Mean Squared Error (RMSE)
     - R-squared (R²)
   - Visualize actual vs predicted prices

---

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/car-price-prediction.git
   cd car-price-prediction
   ```
Install dependencies:
   ```bash
   pip install -r requirements.txt

   ```
Place your dataset CSV file (e.g., car_data.csv) in the project folder.

Run the main script:
   ```bash
   python car_price_prediction.p
   ```
Results
The Random Forest Regressor achieved a Mean Squared Error (MSE) of approximately 0.035 (on scaled data), indicating strong predictive performance.

Visualizations show close alignment between actual and predicted car prices.

Libraries Used
Pandas

NumPy

Scikit-learn

Matplotlib

Seaborn


Future Improvements
Hyperparameter tuning for Random Forest and other models

Feature engineering (e.g., extracting brand from car names)

Use cross-validation for more robust evaluation
