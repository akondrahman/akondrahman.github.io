---
title: "An Empirical Study of Task Infections in Ansible Scripts"
collection: publications
permalink: /publication/emse2024-tidal
date: 2024-01-20
venue: 'Empirical Software Engineering Journal'
paperurl: '/files/papers/emse2024-tidal.pdf'
authors: Akond Rahman, Dibyendu Brinto Bose, Yue Zhang, Rahul Pandita 
year: 2024
index: 69
--- 
**Context**: Despite being beneficial for managing computing infrastructure at scale, Ansible scripts include security weaknesses, such as hard-coded passwords. Security weaknesses can propagate into tasks, i.e., code constructs used for managing computing infrastructure with Ansible. Propagation of security weaknesses into tasks makes the provisioned infrastructure susceptible to security attacks. A systematic characterization of task infection, i.e., the propagation of security weaknesses into tasks, can aid practitioners and researchers in understanding how security weaknesses propagate into tasks and derive insights for practitioners to develop Ansible scripts securely. 

**Objective**: *The goal of the paper is to help practitioners and researchers understand how Ansible-managed computing infrastructure is impacted by security weaknesses by conducting an empirical study of task infections in Ansible scripts.*

**Methodology**: We conduct an empirical study where we quantify the frequency of task infections in Ansible scripts. Upon detection of task infections, we apply qualitative analysis to determine task infection categories. We also conduct a survey with 23 practitioners to determine the prevalence and severity of identified task infection categories. With logistic regression analysis, we identify development factors that correlate with presence of task infections. 

**Results**: In all, we identify 1,805 task infections in 27,213 scripts. We identify six task infection categories: anti-virus, continuous integration, data storage, message broker, networking, and virtualization. From our survey, we observe tasks used to manage data storage infrastructure perceived to have the most severe consequences. We also find three development factors, namely age, minor contributors, and scatteredness to correlate with the presence of task infections.

**Conclusion**: Our empirical study shows computing infrastructure managed by Ansible scripts to be impacted by security weaknesses. We conclude the paper by discussing the implications of our findings for practitioners and researchers. 