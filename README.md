# Grade Predictor:  Analyzing Student Performance 

## Problem Statement
This project aims to predict the academic performance of Portuguese high school students using various machine learning algorithms. Given a dataset containing attributes of 396 students, the objective is to develop classification algorithms that identify whether a student performs well in the final grade exam. Different machine learning models will be evaluated on the dataset to determine their effectiveness.

*Note: A portion of the code was inspired by Abhishek Malik (abhishekmalik20).*

## Dataset Description
The dataset contains student information related to grades, demographics, social factors, and school-related features. The data was collected using school reports and questionnaires. Two datasets are provided for two distinct subjects: Mathematics (mat) and Portuguese language (por). The target attribute G3 represents the final year grade, which is strongly correlated with attributes G2 and G1, representing grades from the first and second periods respectively.

### Attribute Information
- School: Student's school ('GP' - Gabriel Pereira or 'MS' - Mousinho da Silveira)
- Sex: Student's sex ('F' - female or 'M' - male)
- Age: Student's age (numeric: from 15 to 22)
- Address: Student's home address type ('U' - urban or 'R' - rural)
- Famsize: Family size ('LE3' - less than or equal to 3 or 'GT3' - greater than 3)
- Pstatus: Parent's cohabitation status ('T' - living together or 'A' - apart)
- Medu: Mother's education (numeric: 0 - none, 1 - primary education, 2 - 5th to 9th grade, 3 - secondary education, 4 - higher education)
- Fedu: Father's education (numeric: 0 - none, 1 - primary education, 2 - 5th to 9th grade, 3 - secondary education, 4 - higher education)
- ... (and so on for other attributes)

## Methodology
The primary goal of this project is to enhance student retention in higher education institutions. By predicting early grades using machine learning and Educational Data Mining, students' progress can be monitored, and necessary support can be provided to improve their learning experience. This predictive approach can help identify at-risk students and enable instructors to provide targeted assistance.

## Machine Learning Algorithms Used
- Linear Regression
- ElasticNet Regression
- Random Forest
- Extra Trees
- SVM
- Gradient Boosted

## Experimental Results (Shuffled)
- Histogram Plot for G3 (Final Grade)
- Pictorial representation of null data
- Count Plot for Student Sex Attribute
- Kernel Density Estimation for Age of Students
- Count Plot for Male & Female students in different age groups
- Count Plot for students from Urban & Rural Regions
- Impact of age on final grade
- Comparison of urban and rural students' performance
- Relationship between Previous Failures and Final Grade(G3)
- Family Education vs Final Grade(G3)
- Higher Education vs Final Grade(G3)
- Go Out vs Final Grade(G3)
- Reason for choosing school vs Students Count

## Citation
P. Cortez and A. Silva. Using Data Mining to Predict Secondary School Student Performance. In A. Brito and J. Teixeira Eds., Proceedings of the 5th FUture BUsiness TEChnology Conference (FUBUTEC 2008) pp. 5-12, Porto, Portugal, April 2008, EUROSIS, ISBN 978-9077381-39-7.
