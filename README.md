# Logic-based Explanations for Linear Support Vector Classifiers with Reject Option #

This repository contains example implementations of logic-based explanations for linear support vector classifiers with reject option.

## Description ##
Support Vector Classifier (SVC) is a well-known Machine Learning (ML) model for linear classification problems. It can be used in conjunction with a reject option strategy to reject instances that are hard to correctly classify and delegate them to a specialist. This further increases the confidence of the model. Given this, obtaining an explanation of the cause of rejection is important to not blindly trust the obtained results. We propose a logic-based approach with formal guarantees on the correctness and minimality of explanations for linear SVC with reject option. We evaluate our approach by comparing it to Anchors, which is a heuristic algorithm for generating explanations.
## Examples ##
Examples can be found within the repository for a total of 6 different datasets:

- Iris
- Vertebral Column (2 Class)
- Wine
- Pima Indians Diabetes
- Breast Cancer Wisconsin
- Sonar

## Dependencies ##
- numpy
- pandas
- scikit-learn
- pulp
- anchor-exp
