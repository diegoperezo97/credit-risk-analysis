# Supervised Machine Learning and Credit Risk

People borrow money to buy houses, automobiles, establish businesses, and further their education all across the world. Loans are a necessary aspect of contemporary society, but they also give banks and other lending organizations with an opportunity and a difficulty. On the one hand, loans produce revenue from the interest they earn, but there is a danger that borrowers would default on their loans, causing banks to lose money.

Banks have typically assessed lending risk using factors such as income, credit ratings, and collateral assets, but the growth of financial technology, or fintech, has enabled lenders to employ Machine Learning to do so. Machine Learning can sift through a massive quantity of data to make a single judgment, such as whether or not to accept a loan application.

In this module I will construct and analyze different Machine Learning models using Python and the Scikit-learn framework, compare their strengths and shortcomings, and assess how effectively a model classifies and predicts data in this lesson. I will master new abilities like resampling while while improving on old ones like data devouring. These abilities are significant because Machine Learning necessitates simultaneous consideration of all the components of the data analytics jigsaw.

Machine Learning necessitates consideration of the human element as well. After all, even the most thorough study is useless if the stakeholders don't comprehend it. As we go further into the technical aspects, we'll keep the broader picture in mind, and the jigsaw pieces will begin to fall into place.

## Overview of the Analysis

* Fast Loan, a peer-to-peer lending firm, intends to anticipate credit risk using machine learning. Management believes that this will result in a more efficient and dependable loan process. It also believes that Machine Learning will improve the accuracy of identifying qualified loan candidates, resulting in decreased default rates.
* The firm wants me to help the lead Data Scientist put this idea into action. Fast Lending, a peer-to-peer lending services startup, wants to employ machine learning to forecast credit risk, and I'll be building and evaluating many models in my job. Management believes that this will result in a more efficient and dependable loan process. It also believes that machine learning will aid in the more accurate identification of strong credit risk models or algorithms. To get the most out of your models and data, I'll utilize techniques like resampling and boosting. I'll test their performance and see how well your models predict data once I've built and implemented these techniques.
* I'll dig headfirst into Machine Learning algorithms, statistics, and data processing approaches to complete my objective.

### Purpose
* Build and evaluate several Machine Learning models or algorithms to predict credit risk, using techniques such as re sampling and boosting, and evaluate their performance to see how well your models predict data. 

## Results of the Analysis

Table 1. Consolidated results that describe the balanced accuracy score and the precision and recall scores of all six machine learning models

| MACHINE LEARNING MODEL | BALANCED ACCURACY SCORE | PRECISION | RECALL
| ----------- | ----------- | ----------- | -----------
| Naive Random Oversampling | 0.8443807716 | 0.84 | 0.84
| SMOTE Oversampling | 0.8828795124 | 0.88 | 0.88
| Undersampling | 0.9208494208 | 0.92 | 0.92
| Combination (Over and Under) Sampling | 0.8768478321 | 0.88 | 0.88
| Balanced Random Forest Classifier | 0.7587927757 | 0.99 | 0.89
| Easy Ensemble AdaBoost Classifier | 0.917333617 | 30.95 | 0.95


## Summary of the Analysis
