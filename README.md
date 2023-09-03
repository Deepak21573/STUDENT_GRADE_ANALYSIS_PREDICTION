# STUDENT_GRADE_ANALYSIS_PREDICTION
# Objective
Prediction of Portuguese high school pupils' final grades

#Problem Statement
The problem is stated as follows: "Given a dataset containing attributes of 396 Portuguese students, define classification algorithms to determine whether the student performs well on the final grade exam, as well as to evaluate various machine learning models on the dataset."

# Description Of Dataset
These statistics look at secondary school student achievement at two Portuguese schools. The data was gathered through school reports and surveys and includes student grades, demographic, social, and educational aspects. Regarding the performance in two separate disciplines, Portuguese language (por) and mathematics (mat), two datasets are offered. The two data sets were modelled in [Cortez and Silva, 2008] under binary/five-level classification and regression tasks. Note that the goal attribute G3 strongly correlates with the attributes G2 and G1. This is due to the fact that G3 is the final year grade (given at the third period), whereas G1 and G2 correspond to the first and second period grades. Without G2 and G1, it is more challenging to forecast G3, yet such a prediction is far more accurate.

# Attribute Information:
* school - student's school (binary: 'GP' - Gabriel Pereira or 'MS' - Mousinho da Silveira)
* sex - student's sex (binary: 'F' - female or 'M' - male)
* age - student's age (numeric: from 15 to 22)
* address - student's home address type (binary: 'U' - urban or 'R' - rural)
* famsize - family size (binary: 'LE3' - less or equal to 3 or 'GT3' - greater than 3)
* Pstatus - parent's cohabitation status (binary: 'T' - living together or 'A' - apart)
* Medu - mother's education (numeric: 0 - none, 1 - primary education (4th grade), 2 - “ 5th to 9th grade, 3 - “ secondary education or 4 - “ higher education)
* Fedu - father's education (numeric: 0 - none, 1 - primary education (4th grade), 2 - “ 5th to 9th grade, 3 - “ secondary education or 4 - “ higher education)
* Mjob - mother's job (nominal: 'teacher', 'health' care related, civil 'services' (e.g. administrative or police), 'at_home' or 'other')
* Fjob - father's job (nominal: 'teacher', 'health' care related, civil 'services' (e.g. administrative or police), 'at_home' or 'other')
* reason - reason to choose this school (nominal: close to 'home', school 'reputation', 'course' preference or 'other')
* guardian - student's guardian (nominal: 'mother', 'father' or 'other')
* traveltime - home to school travel time (numeric: 1 - <15 min., 2 - 15 to 30 min., 3 - 30 min. to 1 hour, or 4 - >1 hour)
* studytime - weekly study time (numeric: 1 - <2 hours, 2 - 2 to 5 hours, 3 - 5 to 10 hours, or 4 - >10 hours)
* failures - number of past class failures (numeric: n if 1<=n<3, else 4)
* schoolsup - extra educational support (binary: yes or no)
* famsup - family educational support (binary: yes or no)
* paid - extra paid classes within the course subject (Math or Portuguese) (binary: yes or no)
* activities - extra-curricular activities (binary: yes or no)
* nursery - attended nursery school (binary: yes or no)
* higher - wants to take higher education (binary: yes or no)
* internet - Internet access at home (binary: yes or no)
* romantic - with a romantic relationship (binary: yes or no)
* famrel - quality of family relationships (numeric: from 1 - very bad to 5 - excellent)
* freetime - free time after school (numeric: from 1 - very low to 5 - very high)
* goout - going out with friends (numeric: from 1 - very low to 5 - very high)
* Dalc - workday alcohol consumption (numeric: from 1 - very low to 5 - very high)
* Walc - weekend alcohol consumption (numeric: from 1 - very low to 5 - very high)
* health - current health status (numeric: from 1 - very bad to 5 - very good)
* absences - number of school absences (numeric: from 0 to 93)
  
# Methodology
The retention of students at universities, which are esteemed institutions of higher learning, is a major concern. The majority of students who leave universities in their first year do so for lack of adequate support in their undergraduate courses, it has been discovered. This is why the first year of undergraduate study is known as the "make or break" year. A student may become demotivated and decide to drop the course if they receive no help about the complexity and domain of the course.

There is a great need to develop an appropriate solution to assist students retention at higher education institutions. Early grade prediction is one of the solutions that have a tendency to monitor students’ progress in the degree courses at the University and will lead to improving the students’ learning process based on predicted grades.

The learning process of pupils can be enhanced through machine learning and educational data mining. A variety of models can be created to forecast students' grades in the courses they are enrolled in, and these models offer useful information to help students stay enrolled in those courses. Based on this data, a system can recommend that the instructors give those students extra attention. This information can be utilised to identify at-risk pupils early on. This data can also be used to forecast students' grades in various courses so that their performance can be better monitored, which would increase universities' ability to retain students.

Using various packages such as cufflinks, seaborn & matplotlib to represent the data along with different attributes graphically or pictorially to analyse the dataset for predicting the Final Grade(G3).

# Machine Learning Algorithms used
1. Linear Regression
2. ElasticNet Regression
3. Random Forest
4. Extra Trees
5. SVM
6. Gradient Boosted
7. Baseline

# Experimental Results
1. KDE Plot to view all attributes using cufflinks
2. Box Plot to view all attributes using cufflinks
3. Histogram Plot for G3 (Final Grade) using cufflinks
4. Pictorial representation of any null data present in the dataset.
5. Count Plot for Student Sex Attribute
6. Kernel Density Estimation for Age of Students.
7. Count PLot for Male & Female students in different age groups.
8. Count Plot for students from Urban & Rural Region.
9. Does age affect final grade?
10. Do urban students perform better than rural students?
11. Previous Failures vs Final Grade(G3)
12. Family Education vs Final Grade(G3)
13. Higher Education vs Final Grade(G3)
15. Go Out vs Final Grade(G3)
16. Reason vs Students Count
