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

## 2. Prepare
**Data Source:** The dataset consists of anonymized gym member exercise tracking records.
**Data Organization:** The data is structured in a tabular format, including columns for `Workout_Type`, `Calories_Burned`, and `Workout_Frequency`.

## Phase 3: Process (Data Cleaning)
In this phase, the raw dataset was prepared for analysis to ensure data integrity, accuracy and reliability.
* **Tool Used**: Google Sheets.
* **Cleaning Steps Taken**:
* **Standardization:** Standardized column headers for consistency in pivot table mapping.
* **Trimming:** Applied 'Trim whitespace' to remove hidden characters preventing mathematical operations.
* **Numeric Integrity:** Forced numeric data types and verified right-alignment to ensure the software treated the values as numbers.
* **Filter Audit:** Systematically removed null (blank) values and incomplete records to eliminate calculation errors like #DIV/0!. and 'Frequency'.

## Phase 4: Analysis
After ensuring the data was clean, I performed an exploratory analysis to identify trends in member behavior.
* **Pivot Table Configuration**: 
    * Rows: 'Workout_Type'
    * Values: 'Calories_Burned' (Average) and 'Workout_Frequency' (Average)
## Key Findings
* **HIIT** workouts had the highest average calorie expenditure (925.81 calories).
* **Strength** workouts had the highest engagement rate, with an average frequency of 3.36 days per week.
  
## Next Steps
* Transitioning data to Tableau for visualization and dashboard creation.

### Phase 5: Data Visualization
After cleaning and processing the data, I moved to the visualization stage to uncover actionable insights.

* **Tool Used**: Tableau Public
* **Key Visuals**: Created an interactive bar chart showcasing "Average Calories Burned by Workout Type".
* **Key Insights**: 
    * HIIT workouts consistently outperform the 900-calorie benchmark.
    * Implemented interactive filters for Gender and Age, allowing for deep-dive demographic analysis.
* **Final Deliverable**: Published an interactive dashboard to Tableau Public for stakeholder review.

**View the live dashboard here:** [https://public.tableau.com/authoring/GymMemberExerciseAnalysis2026/GymMemberExerciseAnalysis2026#1]

![Dashboard Screenshot]()
