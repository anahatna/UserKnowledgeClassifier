# UserKnowledgeClassifier
KNN-Classification Model

### Background Info:
Work ethic is one of the driving factors in both workplace and academic productivity. Students with strong work ethic are more likely to improve academically. Also, such students are more likely to be desired by employers after graduation since it is essential to assess whether you can fulfill your responsibility. According to research, work ethic for students is linked to improved performance and a greater likelihood for career advancement in the future (Contributor, 2021). This improved performance can be shown through scores on examinations.

We will be looking into a dataset that shows students’ knowledge status alongside a couple of attributes that relate to the students work ethic. Our goal is to try to classify a student’s knowledge status when given only 2 attributes in the dataset. Our classifier will find the nearest neighbours close to our point in the data, find the majority of the user knowledge class among it, and use that to classify our user’s knowledge.

Initially, we thought we would be able to classify the knowledge level based on the STG (study time for goal object) and SCG (degree of repitition for goal object), but we found that those two predictors had no significant relationship, leading to the model not having sufficient accuracy. So, we decided to classify the knowledge level of a user based on their exam performance.

### Dataset:
The dataset we will be using is the User Knowledge Modeling Data Set. This dataset shows the knowledge status of ~400 students on the subject of Electrical DC Machines, including the degree to how they study. Each observation represents a single user, showing the values of their attributes.

### Question (Classification):
Can we predict the UNS level (The knowledge level of the user) if we are given the LPR (exam performance of user for realated objects with goal object) and PEG (exam performance of user for goal objects)?

Relevant columns in the dataset:
STG (The degree of study time for goal object materials)
SCG (The degree of repetition number of user for goal object materials)
STR (The degree of study time of user for related objects with goal object)
LPR (The exam performance of user for related objects with goal object)
PEG (The exam performance of user for goal objects)
UNS (The knowledge level of user)
