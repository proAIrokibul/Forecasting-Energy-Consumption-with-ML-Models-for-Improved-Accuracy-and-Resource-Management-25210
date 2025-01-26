# Forecasting-Energy-Consumption-with-ML-Models-for-Improved-Accuracy-and-Resource-Management-25210
This project focuses on forecasting energy consumption using machine learning models to optimize resource management and improve prediction accuracy. The dataset includes features such as time-based attributes, weather conditions, building specifications, and occupancy levels. The objective is to classify energy consumption patterns based on the provided features and compare the performance of different machine learning classification models.

## **Dataset Overview**
The dataset contains 5,000 samples with the following features:

- **Month**: Numeric representation of the month.
- **Hour**: Hour of the day (0-23).
- **DayOfWeek**: Day of the week (e.g., Monday, Tuesday).
- **Holiday**: Indicates if the day is a holiday.
- **Temperature**: Measured temperature in degrees Celsius.
- **Humidity**: Measured humidity percentage.
- **SquareFootage**: Total square footage of the building.
- **Occupancy**: Number of occupants in the building.
- **HVACUsage**: Indicates HVAC system usage.
- **LightingUsage**: Indicates lighting system usage.
- **RenewableEnergy**: Amount of renewable energy consumed (in kWh).
- **EnergyConsumption**: Total energy consumption (target variable).

## **Project Workflow**
1. **Exploratory Data Analysis (EDA)**:
   - Conducted a detailed analysis of the dataset.
   - Created unique and professional visualizations to uncover patterns and insights.
   - Explored relationships between features like temperature, occupancy, renewable energy, and energy consumption.

2. **Data Preprocessing**:
   - Handled missing values, encoded categorical features, and scaled numerical features.
   - Addressed any data imbalances and prepared the dataset for modeling.

3. **Classification Modeling**:
   - Built and evaluated the following classification models:
     - Logistic Regression
     - Random Forest
     - XGBoost
   - Used metrics such as accuracy, precision, recall, and F1-score to assess model performance.

4. **Model Comparison**:
   - Compared all models based on their evaluation metrics.
   - Visualized the comparison using insightful bar plots for easy interpretation.

## **Results**
### **Logistic Regression**:
- **Classification Report**:
  
          precision    recall  f1-score   support

       0       0.70      0.72      0.71       750
       1       0.71      0.69      0.70       750
accuracy                           0.70      1500
macro avg       0.70      0.70      0.70      1500



