# DECODELABS-INTERNSHIP-Task2
🌍 Life Expectancy Prediction
📂 Dataset Overview
File: 8_Life Expectancy Data.csv

Features:

Country, Year, Status (Developed/Developing)

Life expectancy (target variable)

Health indicators: Adult Mortality, Infant deaths, HIV/AIDS, Hepatitis B, Polio, Diphtheria, BMI, thinness, under-five deaths

Economic indicators: GDP, percentage expenditure, income composition of resources, schooling

Lifestyle indicators: Alcohol consumption, total expenditure

🎯 Project Objective
The aim of this project was to predict life expectancy using socio-economic and health-related features.
Two models were applied:

Linear Regression → R² Score: 82%

Random Forest Regression → R² Score: 96.7%

⚙️ Steps Performed
Data Cleaning

Handled missing values and inconsistencies.

Converted categorical variables (Status) into numerical form.

Exploratory Data Analysis (EDA)

Scatter plots to visualize relationships:

GDP vs Life Expectancy (hue = Status)

Schooling vs Life Expectancy (hue = Status)

Heatmap to analyze correlations among features.

Boxplot to compare Life Expectancy across Developed vs Developing countries.

Modeling

Linear Regression for baseline performance.

Random Forest Regression for improved accuracy and handling non-linear relationships.

Evaluation

Compared R² scores and error metrics.

Random Forest significantly outperformed Linear Regression.

📊 Results
Linear Regression: 82% accuracy

Random Forest Regression: 96.7% accuracy

Strong predictors: Schooling, Income Composition of Resources, GDP, Adult Mortality

Visualizations confirmed clear differences between Developed vs Developing countries.

🚀 How to Run
bash
# Clone repository
git clone <your-repo-link>

# Install dependencies
pip install -r requirements.txt

# Run the script
python life_expectancy_prediction.ipynb
📈 Visualizations
Scatter Plot (GDP vs Life Expectancy) → Shows economic impact on health outcomes.

Scatter Plot (Schooling vs Life Expectancy) → Education strongly correlates with longevity.

Heatmap → Highlights correlations among features.

Boxplot (Status vs Life Expectancy) → Developed countries consistently show higher life expectancy.

📝 Conclusion
Random Forest Regression is highly effective for this dataset, achieving 96.7% accuracy.

Socio-economic factors (GDP, schooling, income composition) play a major role in predicting life expectancy.

Future improvements could include:

Feature engineering (e.g., regional grouping).
Time-series modeling to capture trends over years.
Testing other ensemble methods (XGBoost, Gradient Boosting).
