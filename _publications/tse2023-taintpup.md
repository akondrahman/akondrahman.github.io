---
title: "Detecting and Characterizing Propagation of Security Weaknesses in Puppet-based Infrastructure Management"
collection: publications
permalink: /publication/tse2023-taintpup
date: 2023-04-06
venue: 'IEEE Transactions on Software Engineering (TSE)'
paperurl: '/files/papers/tse2023-taintpup.pdf'
authors: Akond Rahman and Chris Parnin 
year: 2023
index: 66
--- 
Despite being beneficial for managing computing infrastructure automatically, Puppet manifests are susceptible to security weaknesses, e.g., hard-coded secrets and use of weak cryptography algorithms. Adequate mitigation of security weaknesses in Puppet manifests is thus necessary to secure computing infrastructure that are managed with Puppet manifests. A characterization of how security weaknesses propagate and affect Puppet-based infrastructure management, can inform practitioners on the relevance of the detected security weaknesses, as well as help them take necessary actions for mitigation. We conduct an empirical study with 17,629 Puppet manifests with Taint Tracker for Puppet Manifests (TaintPup). We observe 2.4 times more precision, and 1.8 times more F-measure for TaintPup, compared to that of a state-of-the-art security static analysis tool. From our empirical study, we observe security weaknesses to propagate into 4,457 resources, i.e, Puppet-specific code elements used to manage infrastructure. A single instance of a security weakness can propagate into as many as 35 distinct resources. We observe security weaknesses to propagate into 7 categories of resources, which include resources used to manage continuous integration servers and network controllers. According to our survey with 24 practitioners, propagation of security weaknesses into data storage-related resources is rated to have the most severe impact for Puppet-based infrastructure management. 