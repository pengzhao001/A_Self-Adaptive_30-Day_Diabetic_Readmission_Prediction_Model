# Project Title 

Self-adaptive_30-day_Diabetic_Readmission_Prediction_Model

#	Tools: 

Python, Weka, MOA

# Data: 

A de-identified diabetic readmission dataset available on the UCI Machine Learning Repository. 

# Goal

The goal was to build a readmission predictive model that can update itself when new data becomes available so that the model will not be outdated. 

# Comments

Three different online learning algorithms (online Naive Bayes, Hoeffding Tree, Hoeffding Adaptive Tree) were compared in the MOA stream learning platform and the online Naive Bayes outperformed other two algorithms in terms of stability and classification performance. 
The final model has been proven to be able to "remember" old knowledge and adapt to new knowledge.
MOA is a pure Java-based platform with a UI so there is no source code for this project. 

# Publication

This work has been published in the 2017 International Conference on Bioinformatics and Biomedicine (BIBM) IEEE. 
