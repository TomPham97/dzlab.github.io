---
layout: post
comments: true
title: GCP Machine Learning Engineer Certification Preparation Guide
excerpt: Tips and topics to get ready for passing Google Machine Learning Engineer Certification.
categories: certification
tags: [gcp,data,machinelearning,certification]
toc: true
img_excerpt:
---

<center><img alt="Professional Machine Learning Engineer Certification" src='https://templates.images.credential.net/15929551215786304368956491751126.png' width='300' height='300'></center>


I recently passed Google Professional Machine Learning Engineer Certification, during the preparation I went throught lot resources about the exam. The exam is relatively eaiser than the Data engineer certification exam as the questions are more direct (almost no ambigous question) but it has 60 questions instead of the typical 50. It focuses on the following areas:

- Knowledge of ML concepts, problems (classification vs regression), tools (sklearn vs Tensorflow)
- Knowledge of GCP ML products (AI Platform, ML APIs, BQML) and when to use them.
- Knowledge of MLOps concepts (e.g. Continuous training) and tools (TFX vs Kubeflow).

I could not find a comprehensive resource that covers all aspect of the exam when I started preparing. I had to go over a lot of Google Cloud products page and general Machine Learning resources and at no point I felt ready as both topics are huge. Here I will try to provide a summary of the resources I did found helpful for passing the exam.


## Machine Learning
Big part of the exam are general ML questions that touches concept not specific to Google. This is a huge topic by itself but it should be enough for the exam to go over most of the materials in [Google ML Crash Course](https://developers.google.com/machine-learning/)
- Introduction to Machine Learning Problem Framing - [link](https://developers.google.com/machine-learning/problem-framing)
- Data Preparation and Feature Engineering for Machine Learning - [link](https://developers.google.com/machine-learning/data-prep)
- Clustering in Machine Learning - [link](https://developers.google.com/machine-learning/clustering)
- Recommendation Systems - [link](https://developers.google.com/machine-learning/recommendation)
- Testing and Debugging in Machine Learning - [link](https://developers.google.com/machine-learning/testing-debugging)

Also you should get familliar with Privacy in Machine Learning - [link](https://ai.google/responsibilities/responsible-ai-practices/?category=privacy)

### AI Explanations
[Explainable AI](https://cloud.google.com/explainable-ai) is another topic to know about and the different techniques available to explain a model.
- For structured data, Shapely is a popular technique to use
- Integrated ingredients can be used for large feature spaces;
- For images data, use integrated gradients for pixel-level explanations or XRAI for region-level explanations.

Also, an important tool to know about is [WhatIf Tool](https://pair-code.github.io/what-if-tool/) — when do you use it? How do you use it? How do you discover different outcomes? How do you conduct experiments?

## Google Cloud

Here is a flow chart to help with deciding what Google ML product to use depending on the situation:

![gcp-ml-decision-flow]({{ "assets/2022/01/20220108-gcp-ml-decision-flow.svg" | absolute_url }}){: .center-image }

## Certification SWAG
After passing the exam, you can choose one of the official certification swags:

![ml-engineer-certification-swags]({{ "assets/2022/01/20220108-certification-swags.png" | absolute_url }}){: .center-image }
