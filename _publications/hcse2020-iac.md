---
title: "Characterizing Co-located Insecure Coding Patterns in Infrastructure as Code Scripts"
collection: publications
permalink: /publication/hcse2020-iac
date: 2020-08-10
venue: 'Workshop on Human Centric Software Engineering and Cyber Security, co-located with the 35th IEEE/ACM International Conference on Automated Software Engineering (ASE)'
paperurl: '/files/papers/colocation-hcse2020.pdf'
authors: Farzana Ahamed Bhuiyan and Akond Rahman
year: 2020
index: 39
--- 
Insecure coding patterns (ICPs), such as hard-coded passwords can be inadvertently introduced in infrastructure as code (IaC) scripts, providing malicious users the opportunity to attack provisioned computing infrastructure. As performing code reviews is resource-intensive a characterization of co-located ICPs, i.e., ICPs that occur together in a script can help practitioners to prioritize their review efforts and mitigate ICPs in IaC scripts. *The goal of this paper is to help practitioners in prioritizing code review efforts for infrastructure as code (IaC) scripts by conducting an empirical study of co-located insecure coding patterns in IaC scripts.* We conduct an empirical study with 1613, 2764, and 2845 Puppet scripts respectively collected from three organizations namely, Mozilla, Openstack, and Wikimedia. We apply association rule mining to identify co-located ICPs in IaC scripts. We observe 17.9%, 32.9%, and 26.7% of the scripts to include co-located ICPs respectively, for Mozilla, Openstack, and Wikimedia. The most frequent co-located ICP category is hard-coded secret and suspicious comment. Practitioners can prioritize code review efforts for IaC scripts by reviewing scripts that include co-located ICPs.