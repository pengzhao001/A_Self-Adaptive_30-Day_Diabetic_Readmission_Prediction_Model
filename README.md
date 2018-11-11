## Project Title 

A self-adaptive 30-day diabetic readmission prediction model based on incremental learning

##	Tools 

Python, Weka, MOA

## Data

A de-identified diabetic readmission dataset available on the UCI Machine Learning Repository. https://archive.ics.uci.edu/ml/datasets/diabetes+130-us+hospitals+for+years+1999-2008

## Background

Hospital readmission is defined is hospitalized again after being discharged from an initial admission within a short period (normally 30 days). Readmissions within 30 days account for $15 billion in Medicare expenditures annually in the US. Readmission predictive models can help to target the limited medical resources to high-risk patients to help reduce readmissions. With the volume of medical data keeps growing, readmission predictive models built with historical data can get outdated and become less accurate over time. It's expensive to re-train models manually in health care settings. 

## Goal

The goal was to build a readmission predictive model that can update itself when new data becomes available so that the model will not be outdated. 

## Description

This problem was treated as an online/incremental learning problem. Three different online learning algorithms (online Naive Bayes, Hoeffding Tree, Hoeffding Adaptive Tree) were compared in the MOA stream learning platform and the online Naive Bayes outperformed other two algorithms in terms of stability and classification performance. The final model has been proven to be able to "remember" old knowledge and adapt to the latest knowledge.

## Publication

This work has been published in the 2017 International Conference on Bioinformatics and Biomedicine (BIBM) IEEE.

## Note

Weka and MOA are pure Java-based machine learning/stream learning platforms with UI so there is no source code for the modeling part. Python was used for data preprocessing only in this project. 

