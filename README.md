# Predicting Schizophrenia Symptom Severity Using Smartphone-Based Digital Phenotyping

## Overview
This repository presents an applied machine learning project that compares **single-task learning (STL)** and **multi-task learning (MTL)** models for predicting generalised schizophrenia symptom severity using smartphone-based digital phenotyping data.

The project evaluates whether multi-task learning improves prediction performance in real-world mental health datasets, which are often sparse and highly personalised.

## Research Question
Do multi-task learning models outperform single-task learning models when predicting generalised symptom severity using smartphone-based digital phenotyping data?

## Methodology
- Feature engineering from smartphone-based behavioural data
- Model implementation:
  - Single-task model: LassoCV
  - Multi-task model: MultiTaskLassoCV
- Performance evaluation using Root Mean Square Error (RMSE)
- Statistical significance testing using the Wilcoxon signed-rank test

## Dataset
The dataset used in this project is publicly available on Kaggle:

https://www.kaggle.com/datasets/dartweichen/crosscheck

Due to its size, the dataset is not stored in this repository. Users should download it from Kaggle and place it in the `data/` directory.

## Impact
This work contributes to improved understanding of model selection for digital mental health applications and supports the development of more accurate AI-driven healthcare tools.

## Author
**Olajumoke Akinremi**  
Data Scientist | Digital Health Researcher  
Founder & Director (Digital Programmes), Havilah Grace Foundation
