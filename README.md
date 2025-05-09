**🎓 Education Recommendation System**
This project is a Machine Learning-based Education Recommendation System designed to assist students in discovering suitable career paths and relevant learning resources based on their academic performance and other attributes.

** Features**
Predicts the Top 5 most suitable career fields for a student

Takes into account multiple parameters:

Subject-wise academic scores

Gender

Part-time job status

Absenteeism

Extracurricular activity participation

Weekly self-study hours

Recommends online courses based on the predicted career fields

Built using Python, Flask, and Machine Learning

**🧠 Model Development & Selection**
We experimented with multiple machine learning models including:

Logistic Regression

Decision Tree

Support Vector Machine

K-Nearest Neighbors

Naive Bayes

Random Forest

📊 After evaluating all models based on accuracy, Random Forest achieved the highest accuracy, and was selected for final deployment due to its superior performance and robustness across test cases.

The model was then serialized using Pickle along with the scaling pipeline for easy integration into the Flask web app.

**⚙️ Technologies Used**
Python

Flask

Scikit-learn

NumPy, Pandas

Pickle (for model serialization)

HTML/CSS (Jinja2 Templates)

**🎯 Target Career Predictions Include**
Lawyer

Doctor

Government Officer

Artist

Software Engineer

Teacher

Business Owner

Scientist

Banker

Writer

Accountant

Designer

Construction Engineer

Game Developer

Stock Investor

Real Estate Developer

Unknown (for exploratory paths)

**📈 Future Improvements**
Add login/auth system for personalized recommendations

Integrate real-time course APIs (e.g., Coursera, Udemy)

Build a dashboard for visualizing student performance

Upgrade frontend using React or Vue for a better UI experience
