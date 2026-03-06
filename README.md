# Gym Member Retention Analysis (Capstone Project)

## Phase 1: ASK
### Business Task
To identify key factors that lead to gym member "churn" (canceling a membership) and provide data-driven recommendations to increase retention for "Apex Fitness."

### Key Questions
1. Which member segments (Age, Workout Type, or Diet) are most likely to stop attending?
2. Is there a correlation between Experience Level and workout consistency?
3. How do physical metrics like BMI affect gym usage frequency?

### Tools Used
* **Data Cleaning & Analysis:** Google Sheets
* **Visualization:** Tableau Public
* **Documentation:** GitHub / Kaggle


## Phase 2: Process (Data Cleaning)
In this phase, the raw dataset was prepared for analysis to ensure accuracy and reliability.
* **Tool Used**: Google Sheets.
* **Cleaning Steps Taken**:
    * Standardized column headers for consistency in pivot table mapping.
    * Removed all duplicate records to maintain data integrity.
    * Utilized the 'Trim whitespace' tool to remove hidden characters that prevent mathematical calculations.
    * Performed a filter audit to ensure no null (blank) values remained in key columns like 'Calories' and 'Frequency'.

## Phase 3: Analysis
After ensuring the data was clean, I performed an exploratory analysis to identify trends in member behavior.
* **Pivot Table Configuration**: 
    * Rows: 'Workout_Type'
    * Values: 'Calories_Burned' (Average) and 'Workout_Frequency' (Average)
## Key Findings
* **HIIT** workouts had the highest average calorie expenditure (925.81 calories).
* **Strength** workouts had the highest engagement rate, with an average frequency of 3.36 days per week.
  
## Next Steps
* Transitioning data to Tableau for visualization and dashboard creation.
