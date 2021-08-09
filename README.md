# Topic-Recommendation-System_E-learning-Platform

A Collaborative Filtering Approach Towards Implementation of Topic Recommendation System for an E-Learning Platform ExamLounge.

We will use the ExamLounge dataset, which is composed of integer user level ratings from 1 to 5.

Dataset: We have 2 Dataset csv files named as ExamLounge_Topics.csv and LevelRatings.csv

"ExamLounge_Topics.csv": It contains 3 Columns named as topicId, topic_title and exam & 45,756 Rows.

"LevelRatings.csv": It contains 4 Columns named as userId, topicId, rating, timestamp & 15,323 Rows.

PS: The Data is taken from the Exam Lounge: Ed.Tech Startup in this project.

We extract user rating from the dataset as provided LevelRatings.csv using function getUserRatings with one parameter user and load our dataset using loadExamLoungeLatestSmall function and calculated the popularity ranks using user ratings and topic id.

Please find jupyter notebook contatining Text box above each cell explaining the operations performed.
