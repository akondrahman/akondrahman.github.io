---
title: "Understanding Prompt Quality and Its Relation to LLM-based Code Generation"
collection: publications
permalink: /publication/tse26prompt
date: 2026-09-01
venue: 'IEEE Transactions on Software Engineering (TSE)'
paperurl: '/files/papers/tse26-prompt.pdf'
authors: Antonio Della Porta, Stefano Lambiase, Valeria Pontillo, Joao F. Ferreira, Akond Rahman,Chaiyong Ragkhitwetsagul, Fabio Palomba
year: 2026
index: 88
--- 
Prompt engineering has emerged as a key practice to guide Large Language Models (LLMs) in code generation tasks, under the assumption that better prompts yield better outputs. Yet little is known about which characteristics of prompts actually drive variations in output quality. In this paper, we take a first step toward addressing this gap by investigating how measurable properties of prompts relate to the quality of generated code. We conducted an empirical study of real-world, single-turn interactions between developers and ChatGPT collected from GitHub. Prompts were characterized along readability and structural dimensions, while output quality was measured as the conceptual consistency to committed code, perceived usefulness, and correctness. Regression analysis shows that readability metrics are strong predictors of usefulness and correctness, whereas structural features such as the number of sentences and task type significantly affect conceptual consistency. Overall, our findings provide evidence that prompt quality is multi-dimensional and that measurable readability-related and structural prompt properties can serve as indicators of the correctness, usefulness, and conceptual consistency of LLM-generated code in software engineering.