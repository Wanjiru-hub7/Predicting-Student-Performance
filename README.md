# Student Performance Prediction

## About the Project
This project is about predicting the perfomance of the students based on various factors like study time, past grades, and other school-related factors. The  idea is to see which students may need extra help early.

## Dataset Info
- The dataset has the following features: attendance, study hours, Previous grade, Extracurricular activities, Parental support, Final grade, and online class(ture/false)
- The target is the final grade.

## What I Did
- Explored the dataset by checking for any missing value, outliers and incorrect datatypes
- I cleaned it by dropping the missing values and created visualizations for the outliers
- Created new features that would be meaningful to the dataset and encoded categorical data.
- Removed highly correlated features using VIF.
- Split the data (80% training, 20% testing).
- Trained a machine learning model using the 80%
- Evaluated it using accuracy, precision, recall, and F1 score.

## Results
The model didn’t perform very well as the accuracy was 0.38 meaning it was 38% accurate, which means it wasn’t able to pick up strong patterns from the data. This shows that the dataset might need better features or a different model.

## Done By
Wanjiru Gatume
