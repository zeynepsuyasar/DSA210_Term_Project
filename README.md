# DSA210 Term Project - "Step Count and Cycle Analysis"
Zeynep Su Yaşar 30694

# Motivation  
This project is focused on examining how different phases of the menstrual cycle relate to physical activity, specifically looking at daily step counts. By understanding these connections, we can develop personalized health strategies and improve how we plan our activities. The aim is to apply data science methods to uncover trends and relationships that could boost health tracking and awareness.

# Data Source  
The data was gathered from Apple’s Health Application:  
1. Menstrual Cycle Data: This dataset includes daily records from 2020 to now, featuring a binary indicator (Cycle Yes/No) for days within the menstrual cycle.  
2. Step Count Data: This dataset tracks daily step totals from 2020 to the present. Both datasets were exported as CSV files and combined for analysis. To protect privacy, only necessary data columns were kept, and sensitive information was removed.

# Data Analysis  
The project was carried out in several steps: 
1. Data Cleaning: Handled missing and duplicate entries and synchronized the datasets using the Dates column.  
2. Feature Engineering: Created additional columns like Day of Week, Month, and Is Weekend to enhance the dataset.  
3. Exploratory Data Analysis (EDA): Employed descriptive statistics, line charts, box plots, and histograms to analyze trends and distributions.  
4. Correlation Analysis: Explored the relationships between step counts and menstrual cycle phases to validate hypotheses.  
5. Machine Learning:  
   * Random Forest Classifier: Achieved an accuracy of 85% and an ROC AUC score of 0.92.  
   * XGBoost Classifier: Achieved an accuracy of 87% and an ROC AUC score of 0.94, surpassing the Random Forest model.

# Findings  
1. There are differences in step counts between menstrual cycle days and non-cycle days, revealing clear patterns.  
2. The XGBoost model showed subtle differences, highlighting the effectiveness of advanced algorithms in predictive analysis.  
3. Feature engineering, especially the addition of contextual variables like Is Weekend, greatly improved model performance.

# Future Work
1. Add More Features: I could Include extra health indicators like heart rate, sleep habits, and stress levels.  
2. Gather More Data: I should utilize long-term data to identify trends over time.  
3. Try Out Different Algorithms: I could Investigate deep learning techniques for better accuracy and scalability.  


