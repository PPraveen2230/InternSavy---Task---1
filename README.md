# InternSavy---Task---1
Use classification technique for prediction of Graduate admissions from an Indian perspective



M. S. Acharya, A. Armaan and A. S. Antony, "A Comparison of Regression Models for Prediction of Graduate Admissions," 2019 International Conference on Computational Intelligence in Data Science (ICCIDS), Chennai, India, 2019, pp. 1-5, doi: 10.1109/ICCIDS.2019.8862140.

Abstract: Prospective graduate students always face a dilemma deciding universities of their choice while applying to master's programs. While there are a good number of predictors and consultancies that guide a student, they aren't always reliable since decision is made on the basis of select past admissions. In this paper, we present a Machine Learning based method where we compare different regression algorithms, such as Linear Regression, Support Vector Regression, Decision Trees and Random Forest, given the profile of the student. We then compute error functions for the different models and compare their performance to select the best performing model. Results then indicate if the university of choice is an ambitious or a safe one.

URL: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8862140&isnumber=8862005

The Dataset's parameters included are :

GRE Scores (out of 340): This refers to the scores obtained by a student in the Graduate Record Examination (GRE), which is a standardized test commonly used for admission into graduate programs. The scores range from 0 to 340, with higher scores indicating better performance.

TOEFL Scores (out of 120): This refers to the scores obtained by a student in the Test of English as a Foreign Language (TOEFL), which measures English language proficiency for non-native English speakers. The scores range from 0 to 120, with higher scores indicating better English language skills.

University Rating (out of 5): This represents the rating or reputation of the university or institution from which the student graduated or is applying to. It is usually based on various factors such as research output, faculty quality, infrastructure, and academic performance. The rating ranges from 1 to 5, with higher values indicating higher ratings or better universities.

Statement of Purpose and Letter of Recommendation Strength (out of 5): This refers to the perceived strength or quality of the student's statement of purpose and letter of recommendation. It is usually assessed by the admissions committee or reviewers based on the content, clarity, coherence, and strength of recommendations. The scores range from 1 to 5, with higher values indicating stronger statements and recommendations.

Undergraduate GPA (out of 10): This represents the Grade Point Average (GPA) achieved by the student during their undergraduate studies. The GPA is a numerical representation of a student's academic performance, typically ranging from 0 to 10. Higher values indicate higher GPAs, reflecting better academic achievement.

Research Experience (either 0 or 1): This indicates whether the student has prior research experience or not. It is represented as a binary variable, where 0 typically means no research experience and 1 means the student has research experience.

Chance of Admit (ranging from 0 to 1): chance of admit is a parameter that was asked to individuals (some values manually entered) before the results of the application. Think of it this way, with all the scores and other documents you have, you are interested in feeding the data to a ML model and see what it predicts. Basically, you are allowing it to make a prediction regarding your chance of admit so that you can understand what your own chances are. I do understand that eventually it is entirely your decision whether you choose to apply to a particular university or not, however this dataset was only created to be fed into different ML models and check how well it can understand the importance of different parameters before making a prediction.

This dataset is inspired by the UCLA Graduate Dataset. The test scores and GPA are in the older format.
