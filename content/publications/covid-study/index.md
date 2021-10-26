---
title: "Predictive Models of Mortality for Hospitalized Patients With COVID-19: Retrospective Cohort Study"
author: Wang T., Paschalidis A., Liu Q., Liu Y., Yuan Y., Paschalidis I. C.
date: 2020-10-15
slug: covid-study

categories:
  - Journal Articles
  - Research
tags:
  - COVID-19
  - Predictive Modelling
  - Machine Learning

summary: 'A COVID-19 study developing models to predict the mortality of
hospitalized patients using basic demographics and easily obtainable laboratory
data.'

links:
- icon: doi
  icon_pack: ai
  name: Publication
  url: https://doi.org/10.2196/21788
---

## Abstract

**Background:**
The novel coronavirus SARS-CoV-2 and its associated disease, COVID-19, have
caused worldwide disruption, leading countries to take drastic measures to
address the progression of the disease. As SARS-CoV-2 continues to spread,
hospitals are struggling to allocate resources to patients who are most at risk.
In this context, it has become important to develop models that can accurately
predict the severity of infection of hospitalized patients to help guide triage,
planning, and resource allocation.

**Objective:**
The aim of this study was to develop accurate models to predict the mortality of
hospitalized patients with COVID-19 using basic demographics and easily
obtainable laboratory data.

**Methods:**
We performed a retrospective study of 375 hospitalized patients with COVID-19 in
Wuhan, China. The patients were randomly split into derivation and validation
cohorts. Regularized logistic regression and support vector machine classifiers
were trained on the derivation cohort, and accuracy metrics (F1 scores) were
computed on the validation cohort. Two types of models were developed: the first
type used laboratory findings from the entire length of the patient’s hospital
stay, and the second type used laboratory findings that were obtained no later
than 12 hours after admission. The models were further validated on a
multicenter external cohort of 542 patients.

**Results:**
Of the 375 patients with COVID-19, 174 (46.4%) died of the infection. The study
cohort was composed of 224/375 men (59.7%) and 151/375 women (40.3%), with a
mean age of 58.83 years (SD 16.46). The models developed using data from
throughout the patients’ length of stay demonstrated accuracies as high as 97%,
whereas the models with admission laboratory variables possessed accuracies of
up to 93%. The latter models predicted patient outcomes an average of 11.5 days
in advance. Key variables such as lactate dehydrogenase, high-sensitivity
C-reactive protein, and percentage of lymphocytes in the blood were indicated by
the models. In line with previous studies, age was also found to be an important
variable in predicting mortality. In particular, the mean age of patients who
survived COVID-19 infection (50.23 years, SD 15.02) was significantly lower than
the mean age of patients who died of the infection (68.75 years, SD 11.83;
P<.001).

**Conclusions:**
Machine learning models can be successfully employed to accurately predict
outcomes of patients with COVID-19. Our models achieved high accuracies and
could predict outcomes more than one week in advance; this promising result
suggests that these models can be highly useful for resource allocation in
hospitals.