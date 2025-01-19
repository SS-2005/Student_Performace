# Student Performance Prediction Model

## Objective
This project aims to develop a machine learning model to predict students' academic performance (final grades) based on various factors such as age, gender, study habits, attendance, and more.

## Features
- Handles missing values by imputing with the mean.
- Encodes categorical variables like gender into numerical format.
- Uses a Random Forest Regressor for prediction.
- Evaluates model performance using Mean Squared Error.
- Allows user input to predict the final grade for a student based on provided details.

## Files
- **Student Performace.ipynb**: Python script containing the implementation.
- **Student_Performance.csv**: Dataset used for training and testing the model.

## Input Details for Prediction
When running the script, you'll be asked to provide:
- Age (e.g., 16, 18, 20)
- Gender (male/female)
- Study Hour (per day, e.g., 2.5, 3.0)
- Attendance Rate (percentage, e.g., 85, 90)
- Number of Course Failures (e.g., 0, 1, 2)
- Homework Completion Rate (percentage, e.g., 70, 85)

## Output
The outputs the predicted final grade based on the provided details.

## Dataset
The dataset should contain the following columns:
- `age`: Age of the student
- `gender`: Gender of the student (male/female)
- `study_hour`: Daily study hours
- `attendance_rate`: Attendance rate in percentage
- `course_failure`: Number of course failures
- `homework_completion_rate`: Homework completion rate in percentage
- `final_grade`: Final grade of the student (target variable)

## Requirements
pandas
numpy
scikit-learn
