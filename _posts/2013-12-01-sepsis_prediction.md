---
title: "A Temporal-Difference Approach with Unsupervised Data Imputation for Early Sepsis Prediction"
layout: post
date: 2013-12-01 00:00
icon-image: /assets/images/projects/2-sepsis/sepsis-icon.jpg
headerIcon: true
headerImage: false
category: project
projects: true
main: true
hidden: true
description: "Predicting sepsis with imputed medical time series data."
author: Li-Fang
externalLink: false
publish: true
---

Sepsis is one of the leading causes of death in critically ill patients. Each year an estimated 750,000 cases of sepsis or septic shock occur in the United States. The mortality rate of septic patients ranges from 20% to 30%, and accounts for roughly 9.3% of all US deaths. It is challenging to accurately diagnose sepsis onset due to heterogeneous symptoms across patients. For instance, conventional systemic inflammatory response syndrome (SIRS) criteria are widely adopted by physicians, but the specificity is suggested to be as low as 35% in some clinical studies. Therefore, more powerful biomarkers as well as prediction algorithms are needed.


In this work, we aim at predicting sepsis through training a model on historical physiological time series data from Electronic Health Records (EHRs). There are two major challenges. The first one is to handle the incomplete physiological time series data due to the difference in ordering frequency between different clinical measurements. Second, features with higher predictive power should be developed. We first explore and compare serveral unsupervised clustering algorithms for imputing missing values. Next, we propose to extract temporal-difference features based on the imputed data and train a support vector machine (SVM) to identify the states before clinically annotated onsets. The empirical results show that our approach outperforms clinical baselines.

This work was presented by poster at the *Machine Learning for Clinical Data Analysis, Healthcare and Genomics Workshop, Neural Information Processing Systems (NIPS), 2014*.
