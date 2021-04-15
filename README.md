# Ectasia_Prediction
Various scripts utilizing Machine Learning Methods to predict Postoperative Ectasia based on clinical and Finite Element Modeling data. (August 2017-2018)

This repository will host various python scripts made doing research for OptoQuest. My research contributed to software designed to identify high risk patients for various forms of laser eye surgery (particularly LASIK during my time there). This research took place over the course of a year (August 2017-2018) and this is in no way a current assessment of my current ability to write or document code.

The model I chose to use was Logistic Regression with either L2 or no penalties. I investigated each predictor individually as well as combinations in multivariate models. Thresholds for decisions based on the output of the sigmoid function were determined based on various metrics like sensitivity, specificity, the J statistic, and Decision Curves. The project was fueled by very limited data (~300 post-LASIK cases) which I cannot provide due to HIPAA restrictions so cross validation methods was also implemented to assess the efficacy of different models.
