# jubilant-invention-cars-prices
# **Used Car Price Prediction Project**

## Dataset
The dataset used in this project is hosted on Google Drive. You can download it using the link below:

[Download Dataset](https://drive.google.com/drive/folders/1eVR-lSKQyORTf4swDLHTGFek8EHMd97s)

### Instructions
1. Click the link above to open the Google Drive folder.
2. Download the dataset file(s) to your local machine.
3. Place the downloaded file(s) in the `data/` directory before running the notebooks or scripts.


## **Project Overview**
This project applies the CRISP-DM framework to analyze factors influencing used car prices. By leveraging machine learning models and detailed feature engineering, the analysis identifies key drivers of car prices and provides actionable recommendations for a used car dealership to optimize inventory and pricing strategies.

## **CRISP-DM Framework**

1. **Business Understanding**:
   - Objective: Understand what factors make a car more or less expensive.
   - Deliverable: Provide actionable insights for car dealerships to fine-tune inventory and pricing strategies.

2. **Data Understanding**:
   - Dataset: Extracted from a Kaggle dataset containing information on 426,000 used cars.
   - Initial Explorations: Inspected features like region, mileage, year of manufacture, and price for patterns and relationships.

3. **Data Preparation**:
   - Missing value imputation and outlier handling.
   - Feature engineering: Created new variables such as `log_year` and `log_odometer` to capture non-linear relationships.

4. **Modeling**:
   - Applied multiple regression models: Linear Regression, Ridge Regression, Lasso Regression, Decision Tree, and Random Forest.
   - Evaluated performance using metrics like RMSE, MAE, and R².

5. **Evaluation**:
   - Random Forest achieved the best performance with an **R² of 0.88**, highlighting its capability to capture non-linear relationships and feature interactions.

6. **Deployment**:
   - Recommendations were derived from feature importance and model outputs to guide inventory optimization and pricing.

---

## **Key Insights**
- **Factors Driving Car Prices**:
  - **Region**: Regional demand plays the most significant role.
  - **Vehicle Age**: Newer cars (higher `log_year`) are priced higher.
  - **Mileage**: Lower mileage cars (`log_odometer`) command better prices.
- **Model Performance**:
  - Random Forest is the best-performing model, capturing 88% of the variance in car prices.

---

## **Repository Structure**
# **Used Car Price Prediction Project**

## **Project Overview**
This project applies the CRISP-DM framework to analyze factors influencing used car prices. By leveraging machine learning models and detailed feature engineering, the analysis identifies key drivers of car prices and provides actionable recommendations for a used car dealership to optimize inventory and pricing strategies.

## **CRISP-DM Framework**

1. **Business Understanding**:
   - Objective: Understand what factors make a car more or less expensive.
   - Deliverable: Provide actionable insights for car dealerships to fine-tune inventory and pricing strategies.

2. **Data Understanding**:
   - Dataset: Extracted from a Kaggle dataset containing information on 426,000 used cars.
   - Initial Explorations: Inspected features like region, mileage, year of manufacture, and price for patterns and relationships.

3. **Data Preparation**:
   - Missing value imputation and outlier handling.
   - Feature engineering: Created new variables such as `log_year` and `log_odometer` to capture non-linear relationships.

4. **Modeling**:
   - Applied multiple regression models: Linear Regression, Ridge Regression, Lasso Regression, Decision Tree, and Random Forest.
   - Evaluated performance using metrics like RMSE, MAE, and R².

5. **Evaluation**:
   - Random Forest achieved the best performance with an **R² of 0.88**, highlighting its capability to capture non-linear relationships and feature interactions.

6. **Deployment**:
   - Recommendations were derived from feature importance and model outputs to guide inventory optimization and pricing.

---

## **Key Insights**
- **Factors Driving Car Prices**:
  - **Region**: Regional demand plays the most significant role.
  - **Vehicle Age**: Newer cars (higher `log_year`) are priced higher.
  - **Mileage**: Lower mileage cars (`log_odometer`) command better prices.
- **Model Performance**:
  - Random Forest is the best-performing model, capturing 88% of the variance in car prices.

---

## **Repository Structure**
# **Used Car Price Prediction Project**

## **Project Overview**
This project applies the CRISP-DM framework to analyze factors influencing used car prices. By leveraging machine learning models and detailed feature engineering, the analysis identifies key drivers of car prices and provides actionable recommendations for a used car dealership to optimize inventory and pricing strategies.

## **CRISP-DM Framework**

1. **Business Understanding**:
   - Objective: Understand what factors make a car more or less expensive.
   - Deliverable: Provide actionable insights for car dealerships to fine-tune inventory and pricing strategies.

2. **Data Understanding**:
   - Dataset: Extracted from a Kaggle dataset containing information on 426,000 used cars.
   - Initial Explorations: Inspected features like region, mileage, year of manufacture, and price for patterns and relationships.

3. **Data Preparation**:
   - Missing value imputation and outlier handling.
   - Feature engineering: Created new variables such as `log_year` and `log_odometer` to capture non-linear relationships.

4. **Modeling**:
   - Applied multiple regression models: Linear Regression, Ridge Regression, Lasso Regression, Decision Tree, and Random Forest.
   - Evaluated performance using metrics like RMSE, MAE, and R².

5. **Evaluation**:
   - Random Forest achieved the best performance with an **R² of 0.88**, highlighting its capability to capture non-linear relationships and feature interactions.

6. **Deployment**:
   - Recommendations were derived from feature importance and model outputs to guide inventory optimization and pricing.

---

## **Key Insights**
- **Factors Driving Car Prices**:
  - **Region**: Regional demand plays the most significant role.
  - **Vehicle Age**: Newer cars (higher `log_year`) are priced higher.
  - **Mileage**: Lower mileage cars (`log_odometer`) command better prices.
- **Model Performance**:
  - Random Forest is the best-performing model, capturing 88% of the variance in car prices.

---

## **Repository Structure**
├── data/ # Raw and cleaned datasets ├── notebooks/ # Jupyter notebooks with data exploration, modeling, and evaluation ├── scripts/ # Python scripts for preprocessing and modeling ├── outputs/ # Generated reports, plots, and model results ├── Deliverables.docx # Final report with findings and recommendations └── README.md # Project documentation (this file)

# **Jubilant Invention - Used Car Price Prediction**

## **Usage Instructions**
To use this repository, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/nc007-cloud/jubilant-invention-cars-prices.git
   cd jubilant-invention-cars-prices
## Install dependencies:

pip install -r requirements.txt
Prepare the dataset: Place the dataset in your data/ directory.
Ensure the dataset matches the structure expected in the notebooks/EDA_and_Modeling.ipynb notebook.

