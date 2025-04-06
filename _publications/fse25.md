---
title: "Dynamic Application Security Testing for Kubernetes Deployment: An Experience Report from Industry"
collection: publications
permalink: /publication/fse25
date: 2025-04-05
venue: 'ACM International Conference on the Foundations of Software Engineering (FSE) 2025'
paperurl: '/files/papers/fse25.pdf'
authors: Shazibul Islam Shamim, Hanyang Hu, and Akond Rahman  
year: 2025
index: 82
--- 
Practitioners use Kubernetes to automate their software deployments. While Kubernetes enables practitioners to rapidly deploy their software and perform container orchestration efficiently, security of the Kubernetes-based deployment infrastructure is a concern for industry practitioners. A systematic understanding of how dynamic analysis can be used for securing Kubernetes deployments can aid practitioners in securing their Kubernetes deployments. We present an experience report, where we describe empirical findings from three dynamic application security testing (DAST) tools on a Kubernetes deployment used by 'Company-Z'. From our empirical study, we find (i) 3,442 recommended security configurations are violated in 'Company-Z's' Kubernetes deployment; and (ii) of the three studied DAST tools, Kubescape and Kubebench provide the highest support with respect to detecting 14 types of recommended security configurations. Based on our findings, we recommend practitioners to apply DAST tools for their Kubernetes deployments, and security researchers to investigate how to detect configuration violations dynamically in the Kubernetes deployment.         