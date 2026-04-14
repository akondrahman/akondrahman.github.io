---
title: "Configuration Defects in Kubernetes"
collection: publications
permalink: /publication/tse26
date: 2026-03-01
venue: 'IEEE Transactions on Software Engineering (TSE)'
paperurl: '/files/papers/tse26.pdf'
authors: Yue Zhang, Ucchwas Paul, Marcelo d' Amorim, and Akond Rahman
year: 2026
index: 84
--- 
Kubernetes is a tool that facilitates rapid deployment of software. Unfortunately, configuring Kubernetes is prone to errors. Configuration defects are not uncommon and can result in serious consequences. This paper reports an empirical study about configuration defects in Kubernetes with the goal of helping practitioners detect and prevent these defects. We study 719 defects that we extract from 2,260 Kubernetes configuration scripts using open source repositories. Using qualitative analysis, we identify 15 categories of defects, of which 7 have not been reported in previously-studied software systems. We find 8 publicly available static analysis tools to be capable of detecting 8 of the 15 defect categories. We find that the highest precision and recall of those tools are for defects related to data fields. We develop a linter to detect two categories of defects that cause serious consequences, which none of the studied tools are able to detect. Our linter revealed 26 previously-unknown defects that have been confirmed by practitioners, 19 of which have already been fixed. We conclude our paper by providing recommendations on how defect detection and repair techniques can be used for Kubernetes configuration scripts. The datasets and source code used for the paper are publicly available online. 