---
title: "Who Watches the Watchers? On the Reliability of Softwarizing Cloud Application Management"
collection: publications
permalink: /publication/nsdi26
date: 2026-05-14
venue: '23rd USENIX Symposium on Networked Systems Design and Implementation (NSDI'26)'
paperurl: '/files/papers/nsdi26.pdf'
authors: Jiawei Tyler Gu, Zhen Tang, Yiming Su, Bogdan Alexandru Stoica, Xudong Sun, William X. Zheng, Yue Zhang, Akond Rahman, Chen Wang, Tianyin Xu
year: 2026
index: 86
--- 
Modern cloud applications are increasingly managed by software programs, often named ``operators,'' which automate laborious, human-based operations. While operator programs largely prevent human mistakes, their own reliability has unprecedented impact on managed applications. This paper discusses the emerging challenges of operator program reliability on cloud-native platforms like Kubernetes.
Our work is grounded in a rigorous analysis of 412 real-world failures of thirteen Kubernetes operators. We find that challenges of operator reliability come from the multifold complexity of an operator's interactions  with its managed applications, environment, and user interface. Among these, operators' interactions with managed applications are the largest contributor to real-world operator failures, but they are largely overlooked---these interactions are often *ad hoc* and lack well-defined interfaces. We advocate to rethink the management interface of cloud applications and demonstrate this urgent need by showing the prevalence of defects in existing operators. Specifically, we develop a simple testing tool to exercise interactions between operators and the managed cloud applications, which discovered 86 new bugs in six popular Kubernetes operators.