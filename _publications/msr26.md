---
title: "An Empirical Study of Policy as Code: Adoption, Purpose, and Maintenance"
collection: publications
permalink: /publication/msr26
date: 2026-01-01
venue: '23rd International Conference On Mining Software Repositories (MSR) 2026'
paperurl: '/files/papers/msr26.pdf'
authors: Ruben Opdebeeck, Mahmoud Alfadel, Akond Rahman, Yutaro Kashiwa, João F. Ferreira, Raula Gaikovina Kula, and Coen De Roover
year: 2026
index: 83
--- 
Policy as Code (PaC) is an emerging DevOps practice that enables teams to specify organisational and technical policies, such as regulatory compliance, security requirements, and resource limits, through machine-enforceable declarative code.
As PaC gains prominence, practitioners face difficulties in adopting PaC while there remains a limited empirical understanding of how these policies are introduced, what types can be expressed, and how they are maintained in practice.

This paper aims to address this gap through an empirical study of PaC based on 10,560 PaC files from 499 open-source repositories spanning nine PaC tools. We find that PaC is introduced throughout all phases of repository lifecycles, often co-occurring with IaC tools such as Kubernetes or Terraform, with most repositories adopting one of five policy enforcement strategies. Our taxonomy of 12 policy categories reveals that while most policies govern infrastructures and security requirements, they can also express broader constraints related to software development, intellectual property, and expenses. We observe that PaC files are maintained through infrequent yet often substantial changes. 

These findings motivate and support wider and earlier adoption of PaC tools. To this end, the taxonomy of policy categories can serve as a reference to practitioners to identify use cases for PaC in their projects. Meanwhile, our catalogue of enforcement strategies, co-occurring IaC tools, and PaC tool coverage of the taxonomy can inform practitioners when deciding which PaC tool to adopt and how to integrate it in their projects. Finally, our findings motivate future research to automate PaC file generation and maintenance.