---
title: "Share, But Be Aware: Security Smells in Python Gists"
collection: publications
permalink: /publication/icsme2019-gist
date: 2019-09-07
venue: 'International Conference on Software Maintenance and Evolution (ICSME)'
paperurl: '/files/papers/icsme19_gist.pdf'
authors: Md. Rayhanur Rahman, Akond Rahman, and Laurie Williams
year: 2019
index: 29
--- 
Github Gist is a service provided by Github which is used by developers to share code snippets. While sharing, developers may inadvertently introduce security smells in code snippets as well, such as hard-coded passwords. Security smells are recurrent coding patterns that are indicative of security weaknesses, which could potentially lead to security breaches. *The goal of this paper is to help software practitioners avoid insecure coding practices through an empirical study of security smells in publicly-available GitHub Gists*. Through static analysis, we found 13 types of security smells with 4,403 occurrences in 5,822 publicly-available Python Gists. 1,817 of those Gists, which is around 31%, have at least one security smell including 689 instances of hard-coded secrets. We also found no significance relation between the presence of these security smells and the reputation of the Gist author. Based on our findings, we advocate for increased awareness and rigorous code review efforts related to software security for Github Gists so that propagation of insecure coding practices are mitigated. 