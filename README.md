# Türkiye Student Evaluation Analysis - Clustering
This project analyzes student evaluation scores from Gazi University in Ankara, Turkey. The main goal is to apply clustering techniques to group similar students based on their evaluations.

# Dataset Information
The dataset contains a total of 5,820 evaluation scores provided by students. The dataset includes 28 course-specific questions and 5 additional attributes.

# Attribute Information:
instr: Instructor's identifier (values: {1,2,3})
class: Course code (values: {1-13})
repeat: Number of times the student is taking the course (values: {0,1,2,3,...})
attendance: Level of attendance (values: {0, 1, 2, 3, 4})
difficulty: Level of difficulty of the course (values: {1,2,3,4,5})
Q1-Q28: Likert-type questions (values: {1,2,3,4,5})
Example Questions:
Q1: Was the course content and evaluation system provided at the start?
Q2: Were the course aims and objectives clearly stated?
Q3: Was the course worth the amount of credit assigned?
# Project Structure
Data Loading: The dataset is loaded and basic statistics and datatype information are checked.
Preprocessing: The data is checked for missing values and cleaned as necessary.
Exploratory Data Analysis (EDA): Visualizations and statistical analyses are performed to understand the data distribution and relationships between attributes.
Clustering: Different clustering algorithms are applied to group students based on their evaluation responses.
# Libraries Used
Pandas
NumPy
Seaborn
Matplotlib
Instructions to Run
Clone this repository.
Install the required libraries using:

pip install -r requirements.txt
Run the Jupyter notebook using:
arduino

jupyter notebook "8. Turkiye Student Evaluation Analysis - Clustering.ipynb"
Conclusion
The clustering analysis helps to identify patterns in student evaluations, which can be valuable for improving course delivery and understanding student needs.
