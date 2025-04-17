---
title: "On Prescription or Off Prescription?: An Empirical Study of Community-prescribed Security Configurations for Kubernetes"
collection: publications
permalink: /publication/icse25
date: 2025-04-04
venue: 'IEEE/ACM International Conference on Software Engineering (ICSE) 2025'
paperurl: '/files/papers/icse25-k8s.pdf'
authors: Shazibul Islam Shamim, Hanyang Hu, and Akond Rahman  
year: 2025
index: 81
--- 
Despite being beneficial for rapid delivery of software, Kubernetes deployments can be susceptible to security attacks, which can cause serious consequences. A systematic characterization of how community-prescribed security configurations, i.e., security configurations that are recommended by security experts, can aid practitioners to secure their Kubernetes deployments. To that end, we conduct an empirical study with 53 security configurations recommended by the Center for Internet Security (CIS), 20 survey respondents, and 544 configuration files obtained from the open source software (OSS) and proprietary domains.  

From our empirical study, we observe: (i) practitioners can be unaware of prescribed security configurations as 5% ~ 40% of the survey respondents are unfamiliar with 16 prescribed configurations; and (ii) for Company-A and OSS respectively, 18.0% and 17.9% of the configuration files include at least one violation of prescribed configurations. From our evaluation with 5 static application security testing (SAST) tools we find (i) only Kubescape to support all of the prescribed security configuration categories; (ii) the highest observed precision to be 0.41 and 0.43 respectively, for the Company-A and OSS datasets; and (iii) the highest observed recall to be respectively, 0.53 and 0.65 for the Company-A and OSS datasets. Our findings show a disconnect between what CIS experts recommend for Kubernetes-related configurations and what happens in practice. We conclude the paper by providing recommendations for practitioners and researchers. Dataset used for the paper is publicly available online.   