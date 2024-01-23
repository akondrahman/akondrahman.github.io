---
title: "Characterizing Static Analysis Alerts for Terraform Manifests: An Experience Report"
collection: publications
permalink: /publication/secdev2023
date: 2023-11-06
venue: 'IEEE 2023 IEEE Secure Development Conference (SecDev)'
paperurl: '/files/papers/secdev2023.pdf'
authors: Hanyang Hu, Yani Bu, Kristen Wong, Gaurav Sood, Karen Smiley, and Akond Rahman
year: 2023
index: 67
--- 
While Terraform has gained popularity to implement the practice of infrastructure as code (IaC), there is a lack of characterization of static analysis for Terraform manifests. Such lack of characterization hinders practitioners to assess how to use static analysis for their Terraform development process, as it happened for Company A, an organization who uses Terraform to create automated software deployment pipelines. In this experience report, we have investigated 491 static analysis alerts that occur for 10 open source and one proprietary Terraform repositories. From our analysis we observe: (i) 10 categories of static analysis alerts to appear for Terraform manifests, of which five are related to security, (ii) Terraform resources with dependencies to have more static analysis alerts than that of resources with no dependencies, and (iii) practitioner perceptions to vary from one alert category to another while deciding on taking actions for reported alerts. We conclude our paper by providing a list of lessons for practitioners and toolsmiths on how to improve static analysis for Terraform manifests. 