---
title: "Can We Use Software Bug Reports to Identify Software Vulnerability Strategies?"
collection: publications
permalink: /publication/hotsos2020-strategy
date: 2020-07-03
venue: '7th Annual Hot Topics in the Science of Security (HoTSoS) Symposium'
paperurl: '/files/papers/hotsos2020_strategy.pdf'
authors: Farzana Ahamed Bhuiyan, Raunak Shakya, and Akond Rahman
year: 2020
index: 34
--- 
Daily horror stories related to software vulnerabilities necessitates the understanding of how vulnerabilities are discovered. Identification of data sources that can be leveraged to understand how vulnerabilities are discovered could aid cybersecurity researchers to characterize exploitation of vulnerabilities. *The goal of the paper is to help cybersecurity researchers in characterizing vulnerabilities by conducting an empirical study of software bug reports.* We apply qualitative analysis on 729, 908, and 5336 open source software (OSS) bug reports respectively, collected from Gentoo, LibreOffice, and Mozilla to investigate if bug reports include vulnerability discovery strategies, i.e., sequences of computation and/or cognitive activities that an attacker performs to discover vulnerabilities, where the vulnerability is indexed by a credible source, such as the National Vulnerability Database (NVD). We evaluate two approaches namely, text feature-based approach and regular expression-based approach to automatically identify bug reports that include vulnerability discovery strategies.

We observe the Gentoo, LibreOffice, and Mozilla bug reports to include vulnerability discovery strategies. Using text feature-based prediction models, we observe the highest prediction performance for the Mozilla dataset with a recall of 0.78. Using the regular expression-based approach we observe recall to be 0.83 for the same dataset. Findings from our paper provide the groundwork for cybersecurity researchers to use OSS bug reports as a data source for advancing the science of vulnerabilities.   