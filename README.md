# Predicting Student Performance
Project: Statistics, data science and machine learning projects

The project uses basic machine learning techniques to predict student academic outcomes based on a variety of behavioral and academic performance metrics. The goal is to build a model that can predict final exam scores (using regression analysis) and classify students as "pass" or "fail" (classification using logistics regression). 
The project is based on a dataset of 1000 syntheically generated student records. 

# Analysis: 
The prediction model uses several student-related features to estimate academic performance. These features include: "hours_studied," "attendance_percentage," "homework_completion_rate," "social_media_hours,""previous_grade" and "participation_score." These variables are designed to reflect both academic habits and personal behaviors that influence performance. The target vairable for regression is the "final_exam_score" calculated using a synthetic formula designed to simulate real-world academic influence. 

# Sample Results: 
RMSE: 5.42 - on average predictions of this model deviate by 5.42 points from actual scores. 
Classification: 
Accuracy: 66.5% 
Recall ("pass" class): 93% - The model tends to over-predic "pass" (indicating room for improvement or balancing. 
Precision ("pass" class): 69% - The model has moderate precision

# Files: 
student_performance_analysis.ipynb: main jupyter notebook containing the full analysis
student_performance_balanced_final.xlsx: main dataset (1000 students, balanced Pass/Fail)
