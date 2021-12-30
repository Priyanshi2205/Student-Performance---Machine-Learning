# Student-Performance---Machine-Learning

Dataset Description : This data approaches student achievement in secondary education of two Portuguese schools. The data attributes include student grades, demographic, social and school-related features) and it was collected by using school reports and questionnaires. Two datasets are provided regarding the performance in two distinct subjects: Mathematics (mat) and Portuguese language (por). In [Cortez and Silva, 2008], the two datasets were modelled under binary/five-level classification and regression tasks.
Important note the target attribute G3 has a strong correlation with attributes G2 and G1. This occurs because G3 is the final year grade (issued at the 3rd period), while G1 and G2 correspond to the 1st and 2nd period grades. It is more difficult to predict G3 without G2 and G1, but such prediction is much more useful (see paper source for more details).
 
Key Attributes of the Dataset:
school - student's school (binary: 'GP' - Gabriel Pereira or 'MS' - Mousinho da Silveira) (bool: 1 if it's GP else 0)
sex - student's sex (binary: 'F' - female or 'M' - male) (bool: 1 if it's F else 0)
age - student's age (numeric: from 15 to 22)
address - student's home address type (binary: 'U' - urban or 'R' - rural) (bool: 1 if it's U else 0)
famsize - family size (binary: 'LE3' - less or equal to 3 or 'GT3' - greater than 3) (bool: 1 if it's LE3 else 0)
Pstatus - parent's cohabitation status (binary: 'T' - living together or 'A' - apart) (bool: 1 if it's T else 0)
Medu - mother's education (numeric: 0 - none, 1 - primary education (4th grade), 2 â€“ 5th to 9th grade, 3 â€“ secondary education or 4 â€“ higher education)
Fedu - father's education (numeric: 0 - none, 1 - primary education (4th grade), 2 â€“ 5th to 9th grade, 3 â€“ secondary education or 4 â€“ higher education)
traveltime - home to school travel time (numeric: 1 - 1 hour)
studytime - weekly study time (numeric: 1 - 10 hours)
failures - number of past class failures (numeric: n if 1<=n<3, else 4)
schoolsup - extra educational support (binary: yes or no) (bool: 1 if it's Yes else 0)
famsup - family educational support (binary: yes or no) (bool: 1 if it's Yes else 0)
paid - extra paid classes within the course subject (Maths or Portuguese) (binary: yes or no) (bool: 1 if it's Yes else 0)
activities - extracurricular activities (binary: yes or no) (bool: 1 if it's Yes else 0)
nursery - attended nursery school (binary: yes or no) (bool: 1 if it's Yes else 0)
higher - wants to take higher education (binary: yes or no) (bool: 1 if it's Yes else 0)
internet - Internet access at home (binary: yes or no) (bool: 1 if it's Yes else 0)
romantic - with a romantic relationship (binary: yes or no) (bool: 1 if it's Yes else 0)
famrel - quality of family relationships (numeric: from 1 - very bad to 5 - excellent)
freetime - free time after school (numeric: from 1 - very low to 5 - very high)
goout- going out with friends (numeric: from 1 - very low to 5 - very high)
Dalc - workday alcohol consumption (numeric: from 1 - very low to 5 - very high)
Walc - weekend alcohol consumption (numeric: from 1 - very low to 5 - very high)
health - current health status (numeric: from 1 - very bad to 5 - very good)
absences - number of school absences (numeric: from 0 to 93)
G1 - first period grade (numeric: from 0 to 20)
G2 - second period grade (numeric: from 0 to 20)
G3 - final grade (numeric: from 0 to 20)
pass - (bool: 1 if that student passes else 0) output target



Preprocessing and Scaling
PCA and Min Max Scaler


Steps carried out in the models applied on this project :
Importing libraries 
Uploading Dataset
Handle Missing values 
Encoding data - from string to float 
Initialising independent and dependent variables
Splitting the data into testing and training data 
Applying feature scaling if required 
Training of the models 
Compare Models Performance

Model Selection
Classification
KNN - K Nearest Neighbour 
Naive Bayes 
SVM
Regression 
Logistic Regression 
Decision Tree
Random Forest
