---
title: "Security Misconfigurations in Open Source Kubernetes Manifests: An Empirical Study"
collection: publications
permalink: /publication/tosem-k8s
date: 2023-02-10
venue: 'Journal of ACM Transactions on Software Engineering and Methodology (TOSEM)'
paperurl: '/files/papers/tosem-k8s.pdf'
authors: Akond Rahman, Shazibul Islam Shamim, Dibyendu Brinto Bose, and Rahul Pandita
award: Journal-first at ESEC/FSE 2023
year: 2023
index: 64
--- 
Context:Kubernetes has emerged as the de-facto tool for automated container orchestration. Business and government organizations are increasingly adopting kubernetes for automated software deployments. Kubernetes is being used to provision applications in a wide range of domains, such as time series forecasting, edge computing, and high performance computing. Due to such a pervasive presence, Kubernetes-related security misconfigurations can cause large-scale security breaches. Thus, a systematic analysis of security misconfigurations in Kubernetes manifests, i.e., configuration files used for Kubernetes, can help practitioners secure their Kubernetes clusters. Objective: The goal of this paper is to help practitioners secure their Kubernetes clusters by identifying security misconfigurations that occur in Kubernetes manifests. Methodology: We conduct an empirical study with 2,039 Kubernetes manifests mined from 92 open-source software repositories to systematically characterize security misconfigurations in Kubernetes manifests. We also construct a static analysis tool called Security Linter for Kubernetes Manifests (SLI-KUBE) to quantify the frequency of the identified security misconfigurations. Results: In all, we identify 11 categories of security misconfigurations, such as absent resource limit, absent securityContext, and activation of hostIPC. Specifically, we identify 1,051 security misconfigurations in 2,039 manifests. We also observe the identified security misconfigurations affect entities that perform mesh-related load balancing, as well as provision pods and stateful applications. Furthermore, practitioners agreed to fix 60% of 10 misconfigurations reported by us. Conclusion: Our empirical study shows Kubernetes manifests to include security misconfigurations, which necessitates security-focused code reviews and application of static analysis when Kubernetes manifests are developed.   