---
title: "Come for Syntax, Stay for Speed, Understand Defects: An Empirical Study of Defects in Julia Programs"
collection: publications
permalink: /publication/emse2023-julia
date: 2023-03-30
venue: 'Journal of Empirical Software Engineering (EMSE)'
paperurl: '/files/papers/emse2023-julia.pdf'
authors: Akond Rahman, Dibyendu Brinto Bose, Raunak Shakya, and Rahul Pandita
award: Journal-first at FSE 2024
year: 2023
index: 65
--- 
Julia has emerged as a popular programming language to develop scientific software, in part due to its flexible syntax akin to scripting languages while retaining the execution speed of a compiled language. Similar to any programming language, Julia programs are susceptible to defects. However, a systematic characterization of defects in Julia programs remains under-explored. A systematic analysis of defects in Julia programs will act as a starting point for researchers and toolsmiths in building developer tools to improve the quality of Julia programs. To this end, we conduct an empirical study with 742 defects that appear in Julia programs by mining 30,494 commits and 3,038 issue reports collected from 112 open-source Julia projects. From our empirical analysis, we identify 9 defect categories and 7 defect symptoms. We observe certain defect categories to be Julia-specific, e.g., type instability and world age defects. We also survey 52 developers to rank the identified categories based on perceived severity. Based on our empirical analysis, we provide specific recommendations for researchers and toolsmiths.