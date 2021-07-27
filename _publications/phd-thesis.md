---
title: "Anti-patterns in Infrastructure as Code"
collection: publications
permalink: /publication/phd-thesis
date: 2019-06-13
venue: 'NC State University'
paperurl: 'https://repository.lib.ncsu.edu/handle/1840.20/36715'
authors: Akond Rahman 
award: NC State CSC Distinguished Dissertation Award, NC State College of Engineering Distinguished Dissertation Award
year: 2019
index: 25
--- 
In continuous deployment, infrastructure as code (IaC) scripts are used by practitioners to create and manage an automated deployment pipeline that enables information technology (IT) organizations to release their software changes rapidly at scale. Low quality IaC scripts can have serious consequences, potentially leading to wide-spread system outages and service discrepancies. By systematically identifying which characteristics are correlated with low quality IaC scripts, we can identify anti-patterns i.e. recurring practices with negative consequences, which may help practitioners to take informed actions in creating and maintaining defect-free IaC scripts. *The goal of this thesis is to help practitioners in increasing quality of IaC scripts by identifying development and security anti-patterns in the development of infrastructure as code scripts.* Using open source repositories, we conduct five research studies and identify (i) defect categories in IaC scripts; (ii) operations that characterize defective IaC scripts; (iii) code properties that correlate with defective IaC scripts; (iv) development anti-patterns for IaC scripts; and (v) security anti-patterns in IaC scripts that are indicative of security weaknesses.     

From our conducted empirical studies, we observe defect category distribution of IaC scripts are different to that of general purpose programming languages. We observe three operations that characterize defective IaC scripts, namely file system operations, infrastructure provisioning, and user account management. We identify 10 source code properties that correlate with defective scripts, of which size and hard-coded strings as configuration values show the strongest correlation with defective scripts. We identify 13 development anti-patterns that are development activities, which correlate with defective scripts. We also identify 9 security anti-patterns i.e. coding patterns that are indicative of security weaknesses. We hope outcomes of the thesis, i.e., findings, tools, and datasets will facilitate further research in the area of IaC.   