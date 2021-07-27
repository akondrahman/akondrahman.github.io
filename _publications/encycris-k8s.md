---
title: "'Under-reported' Security Defects in Kubernetes Manifests"
collection: publications
permalink: /publication/encycris2021-k8s
date: 2021-02-25
venue: '2nd International Workshop on Engineering and Cybersecurity of Critical Systems (EnCyCriS), co-located with the 43rd International Conference on Software Engineering (ICSE)'
paperurl: '/files/papers/k8s-encycris2021.pdf'
authors: Dibyendu Brinto Bose, Akond Rahman, and Shazibul Islam Shamim
year: 2021
index: 44
--- 
Kubernetes, a container orchestration tool, is reported to help industry practitioners in automated management of cloud infrastructure and rapid deployment of software services. Despite reported benefits, Kubernetes installations are susceptible to security defects, as it occurred for Tesla in 2018. Understanding how frequently security defects appear in Kubernetes installations can help cybersecurity researchers to investigate security-related vulnerabilities for Kubernetes and generate security best practices to avoid them. In this position paper, we first quantify how frequently security defects appear in Kubernetes manifests, i.e., configuration files that are use to install and manage Kubernetes. Next, we lay out a list of future research directions that researchers can pursue. 


We apply qualitative analysis on 5,193 commits collected from 38 open source repositories and observe that 0.79% of the 5,193 commits are security-related. Based on our findings, we posit that security-related defects are under-reported and advocate for rigorous research that can systematically identify undiscovered security defects that exist in Kubernetes manifests. We predict that the increasing use of Kubernetes with unresolved security defects can lead to large-scale security breaches.   