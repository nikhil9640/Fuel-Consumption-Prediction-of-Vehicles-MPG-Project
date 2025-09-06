# Fuel-Consumption-Prediction-of-Vehicles-MPG-Project
The goal of this project is to predict the f uel consumption (Miles per Gallon, MPG) of vehicles based on their technical specifications, attributes such as engine size, weight, and acceleration.

**Accurate predictions of fuel efficiency help in:**
Designing more energy-efficient vehicles.
Understanding how different attributes affect fuel consumption.
Supporting consumers and policymakers in making informed decisions.

**Dataset Overview**
The dataset used for this project is the UCI Auto MPG dataset, which contains information about 398 vehicles manu
factured between 1970 and 1982. 
**Source:** UCI Auto MPG dataset (auto-mpg.data).

**Features:**
cylinders → Number of engine cylinders.
displacement → Engine displacement (cubic inches).
horsepower → Engine horsepower (some missing values).
weight → Vehicle weight (in pounds)(lbs).
acceleration → Time to accelerate from 0–60 mph (in seconds).
model_year → Year of manufacture (last two digits, e.g., 70 = 1970).(70–82)
origin → Region of origin (1 = USA, 2 = Europe, 3 = Japan).
car_name → Car model name (text, not used directly in prediction).
Target: mpg (Miles per Gallon).
MPG (Target Variable) → Miles per Gallon, measure of fuel efficiency.

# Methodology

- Step 1: Imports the necessary libraries
- Step 2: Data Exploration
- Step 2.1: Load dataset
- Step 3: Exploratory Data Analysis (EDA)
- Step 4: Data Preprocessing
- Step 5: Feature Selection / Importance
- Step 6: Model Training & Evaluation
- Step 7: (Optional) Train a Random Forest and compare
- Step 8: Save artifacts
- Step 9: Quick summary print

# Conclusions
**1 Key Influencing Factors:**
Vehicle weight, displacement, horsepower and cylinders are strongly negatively correlated with fuel efficiency (MPG).
Model year and origin (European/Japanese cars) show positive correlation with MPG, reflecting technological improvements and regional efficiency trends.

**2 Model Performance:**
The Linear Regression model explained around 70% of the variance in MPG (R² ≈ 0.7), with an RMSE of ~3–4 MPG.
A Random Forest Regressor provided better performance, capturing nonlinear relationships and interactions between features.

**3 Insights:**
Lighter cars with smaller engines are consistently more f
uel-efficient.
Cars manufactured in later years (post-1975) show higher MPG, indicating technological advancements and regulatory influence.
Japanese and European vehicles were generally more fuel-efficient than American ones during this period.

**4 Practical Implications:**
Vehicle manufacturers can focus on weight reduction and engine optimization to improve fuel efficiency.
Policymakers can use such models to understand long-term fuel consumption trends and guide energy efficiency regulations.
