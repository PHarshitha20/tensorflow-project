# tensorflow-project
# Student-performance-prediction-project

A web-based ML application built with Streamlit to predict student performance using Random Forest models.
The app supports classification (Pass/Fail) and regression (Score Prediction) with interactive visualizations for data insights.

#Project Overview
The Student Performance Prediction App is a web-based machine learning application designed to predict a student’s academic outcomes based on demographic, academic, and socio-economic factors.
This project demonstrates the practical application of AI in education, helping educators and institutions:

Identify at-risk students
Understand key performance drivers
Plan targeted interventions to improve results

 #Features
🔹 Predict Pass or Fail for a student
🔹 Estimate exam score
🔹 Random Forest for both classification & regression
🔹 Interactive visualizations: heatmaps, bar charts, scatter plots
🔹 Custom input for real-time prediction
🔹 GIF animations for results (Pass/Fail)

#Technologies used
Frontend/UI:streamlit
ML/Backend:Python,scikit-learn,pandas,numpy
Visualization:seaborn,matplotlib

#Dataset
UCI Student Performance Dataset [[Link](https://archive.ics.uci.edu/ml/datasets/Student+Performance)]  
Kaggle Student Performance Dataset [[Link](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)]

#Machine Learning Models Used
Random Forest Classifier For predicting Pass/Fail
Random Forest Regressor For predicting Exam Score

#Project Structure
├── app.py                         # Streamlit application
├── StudentPerformanceFactors.csv  # Combined dataset
├── style.css                      # Custom Streamlit styling
├── image_home.jpeg                # Home page image
├── pass.gif / fail.gif             # Project document
├── README.md              # Python dependencies

# Input Fields for Predictions 

Attendance (%)
Hours Studied per Week
Previous Scores (out of 100)
Access to Resources (Low / Medium / High)
Tutoring Sessions per Week

#model performance
classifaction accuracy:~87%
regression RMSE:~1.75

# Team
Developed as part of a Mini Project for B.E. in Artificial Intelligence & Machine Learning at *Canara Engineering College*.
* Reeshal Dsouza (4CB23AI079)
* Sanjana Mahale (4CB23AI087)
* Vrinda Bhaskar Kumtakar (4CB23AI125)
* P Harshitha (4CB23AI064)

  Under the guidance of:
Mr. Arjun K, Assistant Professor, Dept. of AIML

# Future Work
* Add real-time prediction APIs
* Integrate psychological or behavioral metrics
* Deploy on cloud platforms
* Improve model accuracy using ensemble techniques

# License
This project is created for academic purposes and is open for educational extension with proper credit.

"Predict early, act wisely - for a better student future."





