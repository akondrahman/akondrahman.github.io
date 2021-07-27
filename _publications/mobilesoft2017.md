---
title: "Predicting Android Application Security and Privacy Risk with Static Code Metrics"
collection: publications
permalink: /publication/mobilesoft2017
date: 2017-05-15
venue: '4th International Conference on Mobile Software Engineering and Systems (MOBILESoft), co-located with International Conference for Software Engineering (ICSE)'
paperurl: '/files/papers/mobilesoft2017_android.pdf'
authors: Akond Rahman, Priysha Pradhan, Asif Partho, and Laurie Williams
year: 2017
index: 10
--- 
Android applications pose security and privacy risks for end-users. These risks are often quantified by performing dynamic analysis and permission analysis of the Android applications after release. Prediction of security and privacy risks associated with Android applications at early stages of application development, e.g., when the developer(s) are writing the code of the application, might help Android application developers in releasing applications to end-users that have less security and privacy risk. *The goal of this paper is to aid Android application developers in assessing the security and privacy risk associated with Android applications by using static code metrics as predictors.* In our paper, we consider security and privacy risk of Android application as how susceptible the application is to leaking private information of end-users and to releasing vulnerabilities. We investigate how effectively static code metrics that are extracted from the source code of Android applications, can be used to predict security and privacy risk of Android applications. We collected 21 static code metrics of 1,407 Android applications, and use the collected static code metrics to predict security and privacy risk of the applications. As the oracle of security and privacy risk, we used Androrisk, a tool that quantifies the amount of security and privacy risk of an Android application using analysis of Android permissions and dynamic analysis. To accomplish our goal, we used statistical learners, such as radial-based support vector machine (r-SVM). For r-SVM, we observe a precision of 0.83. Findings from our paper suggest that with proper selection of static code metrics, r-SVM can be used effectively to predict security and privacy risk of Android applications.  
