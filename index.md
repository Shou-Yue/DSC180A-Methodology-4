---
layout: default
title: Home
---

# DSC 180A – Methodology 4

**Name and Email**  
ShouTai Yue - syue@ucsd.edu

**Section and Mentor**  
Section A11 - Arya Mazumdar

## Prompts

**What is the most interesting topic covered in your domain this quarter?**  
The most interesting topic this quarter was the study of in-context learning in large language models.
It focused on how transformer models can perform regression or classification tasks without updating
parameters, effectively simulating gradient descent within their activations. This connects 
deep learning and optimization by examining whether models can learn algorithmic behavior directly 
from data patterns.

**Describe a potential investigation you would like to pursue for your Quarter 2 Project.**  
For Quarter 2, I would like to test whether in-context learning applies to non-linear regression
and logistic classification tasks. The investigation would measure how well large language models 
can approximate multiple gradient steps when facing non-linear functions. I would also compare models
of different sizes to see how scale and prompt structure influence learning behavior.

**What is a potential change you’d make to the approach taken in your current Quarter 1 Project?**  
In Quarter 1, the prompts were fully textual and limited to single-step prediction. I would change
this by adding more structured prompts, such as formatted tables or aligned examples, and by increasing
the number of in-context samples. I would also log intermediate activations to observe which model 
components contribute to gradient-like updates during inference.

**What other techniques would you be interested in using in your project?**  
I would like to apply representation probing and activation analysis to study internal computations.
I am also interested in using contrastive prompt experiments and synthetic scaling tests to evaluate 
how different data formats, context lengths, and task complexities affect in-context learning 
performance.
