---
layout: page
title: "Distributed Systems for Financial and Behavioral Data"
doodle: "/hpc.jpg"
permalink: /
---

Data science capstone domain of inquiry (DSC 180AB A15)

Developed by Rod Albuyeh.

---
* TOC
{:toc}

---

# Introduction

This domain of inquiry studies the problem of scaling machine learning 
systems to accommodate large and complex workloads for financial and behavioral 
data, which typically involve tabular data with a focus on time-series and 
categorical transformations. This involves effective cluster 
computing, maximizing resources on undersized nodes, and in many cases both. To 
explore these challenges, we will initially focus on the problem of credit default
prediction in the 
[Freddie Mac Single Family Loan-Level Dataset](https://www.freddiemac.com/research/datasets/sf-loanlevel-dataset) 
where we must: 
1. scale and (where feasible) parallelize our workloads for data preprocessing, feature selection, 
and design matrix generation appropate for different model types.
2. efficiently tune hyperparameters, as well as train and validate models of different types. 
3. automate workflow orchestration.  
4. optionally, leverage non-tabular data such as text.
5. optionally, deploy a custom real-time endpoint for inference. 

In this domain, project proposals will be restricted to the following
areas:
* Scaling, Evaluating, and Maximizing Feature Engineering and Selection Techniques 
* Deep Learning for Tabular Data, Benchmarked Against Classical Methods 
* Generating General Purpose Re-Usable Tools  


## Introduction to the Topic

The first half of the project will focus on the task of exceeding the 
performance of FICO scores in predicting loan-level default in the Freddie
Mac dataset. I will provide code and slides to benchmark against. 

In the latter half of Quarter 1, I will introduce you to distributed frameworks 
like Ray, Modin, and Spark, which will help you scale the work you did in part 1 
to accommodate more data for training and inference, as well as enable more complex
workloads. I will also introduce you to organizing and packaging your python workflows
in ways that enable easy tools sharing, code-reuse, testing, and replication. 


---

# Section Participation

Participation in the weekly discussion section is *mandatory*. Each
week, you are responsible for doing the reading/task assigned in the
[schedule](#schedule). Come to section prepared to ask questions about
and discuss the results of these tasks.

Each week, turn in answers to the weekly questions to Gradescope. These
questions are meant to focus your work for the week and help prepare
you for discussion. If you have questions about your work, please ask
them in section or office hours (I will rarely comment on your
submission).

You are responsible for the entire weekly reading/task, even if
portions are not covered in the weekly questions. The weekly tasks are
the building blocks for the project proposals/assignments due at the
end of the quarter.

---

# Schedule

|Week|Topic|
|--|--|
|1|[Introduction to Credit Risk Forecasting]({{ "weeks/01-Introduction" | absolute_url }})|


---

# Office Hours

Fridays 10-11AM



