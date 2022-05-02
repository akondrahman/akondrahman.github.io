---
title: "Security Smells in Ansible and Chef Scripts: A Replication Study"
collection: publications
permalink: /publication/tosem2021
date: 2021-01-01
venue: 'Journal of ACM Transactions on Software Engineering and Methodology (TOSEM)'
paperurl: 'https://arxiv.org/pdf/1907.07159.pdf'
authors: Akond Rahman, Md. Rayhanur Rahman, Chirs Parnin, and Laurie Williams
award: Covered by Hacking Security News 
year: 2021
index: 41
--- 
Security smells are recurring coding patterns that are indicative of security weakness and require further inspection. As infrastructure as code (IaC) scripts, such as Ansible and Chef scripts, are used to provision cloud-based servers and systems at scale, security smells in IaC scripts could be used to enable malicious users to exploit vulnerabilities in the provisioned systems. *The goal of this paper is to help practitioners avoid insecure coding practices while developing infrastructure as code scripts through an empirical study of security smells in Ansible and Chef scripts.* We conduct a replication study where we apply qualitative analysis with 1,956 IaC scripts to identify security smells for IaC scripts written in two languages: Ansible and Chef. We construct a static analysis tool called SLAC to automatically identify security smells in 50,323 scripts collected from 813 open source software repositories. We also submit bug reports for 1,000 randomly-selected smell occurrences. We identify two security smells not reported in prior work: missing default in case statement and no integrity check. By applying SLAC we identify 46,600 occurrences of security smells that include 7,849 hard-coded passwords. We observe agreement for 65 of the responded 94 bug reports, which suggests the relevance of security smells for Ansible and Chef scripts amongst practitioners. We observe security smells to be prevalent in Ansible and Chef scripts, similar to that of the Puppet scripts. We recommend practitioners to rigorously inspect the presence of the identified security smells in Ansible and Chef scripts using (i) code review, and (ii) static analysis tools. 