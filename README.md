# Practical Application 2 - What drives the price of a car?

## Notebook
[Workbook]([https://www.google.com](https://github.com/krupakmurthy/price_of_car/blob/main/prompt_II.ipynb)) 

### Project Overview
This project aims to analyze a dataset of used cars to identify key factors influencing car prices. The insights derived will help a used car dealership optimize inventory management, set competitive prices, and align with consumer preferences. By leveraging regression models and statistical analysis, actionable recommendations are delivered to the car dealership.

### Objectives
1. Identify the key features driving used car prices (e.g., year, mileage, condition).
2. Develop predictive models to estimate car prices accurately.
3. Provide actionable insights to improve inventory and pricing strategies.

### Dataset Description
Source: Kaggle (reduced version with 426K cars for faster processing).
Key Features:
- Numeric: Price, Year, Odometer, Cylinders.
- Categorical: Drive, Fuel Type, Transmission, Paint Color.
- Challenges: Missing values and outliers in key features like condition, mileage, and price.
  
### Methodology
This project follows the CRISP-DM framework:

1. Business Understanding:
- Determine factors that drive used car prices.
- Provide recommendations to optimize dealership inventory and pricing strategies.
  
2. Data Understanding:
- Explore relationships between features and price using statistical and visual techniques.
  
3. Data Preparation:
- Handle missing values through imputation or categorization.
- Remove outliers to ensure robust model performance.
  
4. Modeling:
- Train and evaluate multiple regression models:
  - Linear Regression
  - Polynomial Regression
  - Lasso Regression
  - Ridge Regression
  - Use feature selection techniques like Sequential Feature Selector and Lasso regularization.
    
5. Evaluation:
- Assess models using metrics such as:
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R2 Score
  
6. Deployment:
- Provide insights and recommendations for dealership operations.

### Key Findings
1. Best Predictive Model
- Polynomial Regression (degree 3) performed best, balancing accuracy and computational efficiency.
2. Feature Importance:
- Year > Cylinders > Odometer > Fuel > Drive
3. Data Challenges
- Missing values and outliers posed significant challenges but were addressed through preprocessing.

### Deployment/ Recommendations
1. Vehicles from recent years consistently command higher prices. Prioritize acquiring these models during inventory restocking, especially if they feature desirable attributes like modern technology or fuel efficiency. So, Focus on newer vehicles
2. Cars with lower odometer readings retain more value and appeal to buyers.
3. Use the predictive model to set competitive and profitable prices.
4. Emphasize vehicles with automatic transmission in your listings, as they positively impact pricing and align with buyer preferences.
5. Promote cars with desirable drive types (e.g. four-wheel drive) as these are associated with higher prices and better performance in specific conditions.
6. Highlight vehicles in good/excellent condition
7. With increasing interest in sustainability, feature fuel-efficient cars and hybrids prominently, as they may attract a growing segment of environmentally conscious buyers. But the cars
   on gas are still on high demand which might continue for few more years.



