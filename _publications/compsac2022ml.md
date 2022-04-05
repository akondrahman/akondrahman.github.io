---
title: "Shifting Left for Machine Learning: An Empirical Study of Security Weaknesses in Supervised Learning-based Projects"
collection: publications
permalink: /publication/compsac2022ml
date: 2022-04-25
venue: '46th IEEE Computer Society Computers, Software, and Applications Conference (COMPSAC)'
paperurl: '/files/papers/compsac2022-ml.pdf'
authors: Farzana Ahamed Bhuiyan, Stacey Prowell, Hossain Shahriar, Fan Wu, and Akond Rahman
year: 2022
index: 56
--- 
 **Context**: Supervised learning-based projects (SLPs), i.e., software projects that use supervised 
 learning algorithms, such as decision trees are useful for performing classification-related tasks. Yet, security weaknesses, 
 such as the use of hard-coded passwords in SLPs, can make SLPs susceptible to security attacks. A characterization of 
 security weaknesses in SLPs can help practitioners understand the security weaknesses that are frequent in SLPs and 
 adopt adequate mitigation strategies. **Objective:** `The goal of this paper is to help 
 practitioners securely develop supervised learning-based projects by conducting an empirical study of security 
 weaknesses in supervised learning-based projects.` **Methodology:** We conduct an empirical study by 
 quantifying the frequency of security weaknesses in 278 open source SLPs. **Results:** We identify 
 22 types of security weaknesses that occur in SLPs. We observe `use of potentially dangerous function` to be the most 
 frequently occurring security weakness in SLPs. Of the identified 3,964 security weaknesses, 23.79% and 40.49% respectively, 
 appear for source code files used to train and test models. We also observe evidence of co-location, e.g., instances of 
 command injection co-locates with instances of potentially dangerous function. **Conclusion:** Based on our 
 findings, we advocate for a _shift left_ 
 approach for SLP development with security-focused code reviews, and application of security static analysis.        