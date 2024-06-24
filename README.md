# berlin-marathon-analysis
Description:

This repository contains the CIS 5450 final project by Caroline Cummings, Cameron Bosio-Kim, and Julia Fremberg. The project investigates the impact of environmental factors on Berlin Marathon race times from 1974 to 2019. Using datasets with runner demographics and weather conditions, the analysis aims to predict marathon finishing times and identify key patterns.

**Datasets:**

1. Berlin Marathon Runner Data:

- Contains information on finish times, gender, age, and year of participation.
- Provides a historical perspective on marathon performance.

2. Berlin Marathon Weather Data:

- Records weather conditions such as temperature, atmospheric pressure, precipitation, sunshine, and cloud cover during each marathon event.
- Helps to correlate weather conditions with race performance.

**Research Objective:**

The objective is to explore correlations between environmental variables (e.g., temperature, precipitation, sunshine, atmospheric pressure) and marathon race times. The analysis includes building models to predict finishing times based on these conditions, with a focus on differentiating results by gender.

**Structure of the Notebook:**

1. Importing and Data Loading:

- Import essential libraries for data processing, analysis, and modeling.
- Load datasets from a shared Google Drive.
- Cleaning and Exploratory Data Analysis (EDA):

2. Inspect and clean the marathon data.
- Process age and time columns for accurate analysis.
- Visualize data to identify patterns and trends.
- Weather Data Processing and EDA:

3. Clean and preprocess weather data.
- Merge marathon and weather datasets for comprehensive analysis.
- Model Building and Evaluation:

4. Construct and evaluate baseline models using linear regression.
- Implement advanced models like Gradient Boosting and Random Forest.
- Perform hyperparameter tuning to optimize model performance.

5. Results and Insights:
- Analyze the performance of different models.
- Identify key factors influencing marathon times.
- Provide practical implications for runners and event organizers.

**Conclusion:**
The findings suggest that demographic factors such as age and gender are stronger predictors of marathon performance than environmental conditions. However, the analysis provides valuable insights for marathon planning and training, highlighting the importance of focusing on individual characteristics and athletic abilities.
