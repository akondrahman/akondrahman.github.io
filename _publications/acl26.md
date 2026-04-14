---
title: "Large Language Models for IT Automation Tasks: Are We There Yet?"
collection: publications
permalink: /publication/acl26
date: 2026-04-01
venue: 'The 64th Annual Meeting of the Association for Computational Linguistics (ACL 2026)'
paperurl: '/files/papers/acl26.pdf'
authors: Md. Mahadi Hassan, John Salvador, Akond Rahman, and Santu Karmaker 
year: 2026
index: 85
--- 
Large language models (LLMs) show promise in code generation, yet their effectiveness for information technology (IT) automation tasks, particularly for tools like Ansible, remains understudied. Existing benchmarks rely primarily on synthetic tasks that fail to capture the needs of practitioners who use IT automation tools, such as Ansible. We present ITABench (IT Automation Task Benchmark), a benchmark of 126 diverse tasks (e.g., configuring servers, managing files) where each task accounts for state reconciliation-a property unique to IT automation tools. ITABench evaluates LLMs' ability to generate functional Ansible automation scripts via dynamic execution in controlled environments. We evaluate 14 open-source and 2 proprietary LLMs, and find GPT-4.1-Mini to be the best performing model with a pass@10 rate of 23.9%. To explain the low performance, we analyze 1,598 execution failures across the evaluated LLMs and identify two main categories of prevalent semantic errors: failures in state reconciliation related reasoning (44.81% combined from variable (12.09%), host (10.92%), path(11.57%), and template (10.23%) issues) and deficiencies in module-specific execution knowledge (24.92% combined from Attribute & parameter (15.35%) and module (9.57%) errors). Our findings reveal key limitations in LLMs' ability to track state changes and apply specialized module knowledge, indicating that reliable IT automation will require major advances in state reasoning and domain-specific execution understanding.