# Predictive Model for Diabetes Classification

## Authors
Jesse Luyan, Shanmei Liu, Aditya Bakshi, Kshitij Doshi

## Project Overview
This project explores the development of a predictive classification model to identify individuals with diabetes based on various health indicators. Using a dataset from the Centers for Disease Control and Prevention (CDC) containing ~400,000 survey responses, we aimed to determine which factors most strongly predict diabetes and create an accurate prediction model.

## Dataset
The dataset includes variables such as:
- **Demographics**: Age, Sex, Income, Education
- **Health Indicators**: BMI, Physical Health, Mental Health, Heart Disease, Stroke
- **Lifestyle Factors**: Smoking, Alcohol Consumption, Fruit and Vegetable Intake, Physical Activity
- **Other**: Cholesterol Levels, Difficulty Walking, Healthcare Access

## Methods
1. **Exploratory Data Analysis**:
   - Variables categorized into binary and numerical.
   - Visualizations created to identify potential predictors.
2. **Model Selection**:
   - K-Nearest Neighbors (KNN) was chosen for its simplicity and effectiveness in predicting categorical outcomes.
   - Cross-validation used to tune hyperparameter `k`.
3. **Model Workflow**:
   - Data split into training and testing sets.
   - Confusion matrix generated to evaluate model accuracy.
4. **Visualization**:
   - Bar plots and histograms compare predictions with actual outcomes.
   - Scatter plots explore relationships between predictors.

## Results
- Selected predictors: Age, BMI, Physical Health, Heart Disease/Attack, Stroke, and Difficulty Walking.
- Model accuracy: **66.7%**, reflecting good predictive performance given a balanced dataset (50% diabetes-positive and 50% diabetes-negative).

### Key Insights
- **Age**: Older individuals are at higher risk.
- **BMI**: Higher BMI correlates with diabetes risk.
- **Physical Health**: Poor physical health increases risk.
- **Lifestyle Factors**: Difficulty walking and heart conditions strongly indicate diabetes.

## Discussion
While the model demonstrates reasonable accuracy, future work could improve performance by incorporating additional impactful variables or exploring alternative machine learning algorithms. The findings reinforce the importance of lifestyle management in diabetes prevention and open new questions about standardizing health metrics.

## Future Work
- Investigate other potential predictors beyond BMI and lifestyle.
- Develop more sophisticated models to handle large-scale health data.
- Explore preventive strategies informed by predictors like difficulty walking.

## Project Files
- **Code and Analysis**: `DSCI100.html`
- **Dataset Source**: CDC survey responses processed for analysis.

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/MgSO477/DSCI100_Diabetes_classification.git
   cd DSCI100_Diabetes_classification
2. Open the DSCI100.html file in a browser to view the full analysis and results.
