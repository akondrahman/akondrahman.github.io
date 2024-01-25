---
permalink: /projects/
title: ""
excerpt: ""
author_profile: true
---

The **P**ractical and **A**ctionable **S**oftware **E**ngineering **R**esearch (**PASER**) group at Auburn University is currently pursuing the following research projects. 



eSLIC: Enhanced Security Static Analysis for Configuration Scripts
======

Abstract 
---
The project will focus on the development of techniques and tools that will automatically detect security weaknesses in configuration scripts developed using a wide range of languages heavily used in industry. Three main tasks will be investigated for this project. First, qualitative analysis is applied in order to determine a comprehensive list of security weaknesses for multiple configuration script languages, and devise static analysis techniques for automatically identifying each category of security weakness. Next, grammar-based parsing and machine learning techniques are applied, evaluated, and integrated into the derived static analysis so that false positives are reduced. Finally, the development context of practitioners from the open source and proprietary domain will be systematically mined to generate actionable alerts and suggestions, which will enable practitioners to fix security weaknesses. Along with the three technical tasks, industry panels will be organized, where practitioners from industry will give feedback on the developed techniques and tools. Findings from the project will be disseminated to government, industry and open source practitioners, as well as to students who are learning about configuration management in graduate and undergraduate level courses related to cybersecurity. 


Relevant Peer-reviewed Publications 
---
- [EMSE 2024](/files/papers/emse2024-taintible.pdf)
- [TSE 2023](/files/papers/tse2023-taintpup.pdf)
- [SecDev 2023](/files/papers/secdev2023.pdf)
- [FIST 2023](/files/papers/fist2023-compiler.pdf)
- [FIST 2023](/files/papers/fist2023-survey.pdf)
- [ICST 2022](/files/papers/icst2022-tama.pdf)
- [SANER 2022](/files/papers/saner2022.pdf)
- [SecDev 2021](/files/papers/secdev2021.pdf)
- [S&P 2021](/files/papers/slic-sp2021.pdf)
- [FIE 2021](/files/papers/fie2021.pdf)
- [QUATIC 2021](/files/papers/quatic2021.pdf)
- [TOSEM 2021](https://arxiv.org/pdf/1907.07159.pdf)
- [HCSE 2020](/files/papers/colocation-hcse2020.pdf)
- [ICSE 2019](/files/papers/icse19_slic.pdf)

Datasets and Software
---
- [TIDAL for Ansible](https://github.com/paser-group/TIDAL/tree/master)
- [TaintPup for Puppet](https://github.com/paser-group/TaintPup)
- [TAMA for Ansible](https://hub.docker.com/r/talismanic/tama)
- [ACID for Puppet](https://hub.docker.com/repository/docker/akondrahman/acid-puppet)
- [SLAC for Ansible](https://hub.docker.com/r/akondrahman/slic_ansible)
- [SLIC for Puppet](https://hub.docker.com/r/akondrahman/ruby_for_sp)
- [Education Materials for the `Secure Software Development` Course](https://hub.docker.com/repository/docker/akondrahman/sec-soft-edu-materials)


Funding Source
---
- [NSF SaTC: Award - 2247141](https://nsf.gov/awardsearch/showAward?AWD_ID=2247141&HistoricalAwards=false)
- NSA Award - H98230-21-1-0175

Resilient Container Orchestration 
======

Abstract
---

Container technologies, such as Docker and LXC are gaining popularity amongst information technology (IT) organizations for deploying software applications. For example, PayPal uses 200,000 containers to manage 700 software applications. For managing these containers at scale, practitioners often use automated container orchestration, i.e, the practice of pragmatically managing the lifecycle of containers with tools, such as Docker Swarm and Kubernetes. As part of this project we are investigating how to help practitioners for resilient container orchestration. As part of this project, we will accomplish three tasks: (i) detecting and repairing security misconfigurations that occur in configuration files used for container orchestration; (ii) build the science of routing-related defects; and (iii) construct education modules to help next generation practitioners in secure and resilient container orchestration.    


Relevant Peer-reviewed Publications 
---
- [MSR 2024](/files/papers/k8s-msr2024.pdf)
- [TOSEM 2023](/files/papers/tosem-k8s.pdf)
- [ENCYCRIS 2021](/files/papers/k8s-encycris2021.pdf)
- [SecDev 2020](https://arxiv.org/pdf/2006.15275.pdf)


Datasets and Software
---
- [Dataset: Container Orchestration Smells for ChatGPT-generated Kubernetes Manifests](https://doi.org/10.6084/m9.figshare.24786711.v1) 
- [Software: SLI-KUBE](https://hub.docker.com/r/akondrahman/sli-kube) 
- [Dataset: Security Misconfiguration in Kubernetes Manifests](https://doi.org/10.6084/m9.figshare.17425478.v3) 
- [Dataset: Vulnerability-related Commits](https://doi.org/10.6084/m9.figshare.13447796.v1)  

Funding Source
---
[NSF CORE:SHF: Award - 2312321](https://nsf.gov/awardsearch/showAward?AWD_ID=2312321&HistoricalAwards=false)



Secure Development of Machine Learning Projects 
======

Abstract
---
The ubiquitous use of machine learning necessitates to make the development process secure. In this project we are exploring so strategies used to secure the development process for traditional software engineering can also be integrated in machine learning development. In particular, we are investigating (i) how to perform logging to diagnose adversarial machine learning attacks and formally verify security specifications in machine learning implementations, (ii) common security weaknesses in machine learning source code, and (iii) identifying testing best practices for automating machine learning deployments.  

Relevant Peer-reviewed Publications 
---
- [ACM TOPS 2022](/files/papers/tops2022.pdf)
- [AI/ML @ COMPSAC2022](/files/papers/bots-mlops2022.pdf)
- [COMPSAC2022](/files/papers/compsac2022-ml.pdf)
- [ENCYCRIS2021](/files/papers/strategy-encycris2021.pdf)
- [HCSE2020](/files/papers/strategy-hcse2020.pdf)
- [HOTSOS2020](/files/papers/hotsos2020_strategy.pdf)


Datasets and Software
---
- [LOPSUL for Python-based Open Source ML Projects](https://github.com/paser-group/MLForensics) 
- [Security Weakness Dataset for Open Source ML Projects](https://figshare.com/s/86bea428698b103afb32) 

Funding Source
---
[NSF SaTC: Award - 2310179](https://nsf.gov/awardsearch/showAward?AWD_ID=2310179&HistoricalAwards=false)


<!-- Building the Foundations of Validation for the Julia Ecosystem 
======

Abstract
---
Software validation activities, such as software testing and static analysis, are resource-consuming. Insights on what categories of defects appear in software can help practitioners understand the nature of software defects and prioritize validation activities accordingly. Defect categorization can provide insights on the nature of defects that appear in Julia programs and how tools related to validation can be constructed. 

Julia is an emerging programming language that was designed to provide programming syntax similar to that of scripting languages, such as Python, with similar program execution speed of compiled languages with low-level memory access, such as C. According to a survey of Stack Overflow users in 2020, Julia is considered as one of the top 10 most loved programming languages. The popularity of Julia as a programming language motivates us to construct validation tools, such as fuzzing tools and static analysis tools so that potential defects can be mitigated early at the development stage. We are applying dynamic analysis tools, such as the American Fuzzy Lop to find bugs in the Julia compiler. We are also creating a security static analysis tool to find security weaknesses in Julia programs. As of today, no security static analysis tools exist for Julia programs. 

Relevant Peer-reviewed Publications 
---
- [HOTSOS2020](/files/papers/hotsos2020_scisoft.pdf)
- [ACMSE2022](/files/papers/julia-acmse2022.pdf)

Datasets and Software
---
To be available soon. 

-->