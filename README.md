# Ensemble-techniques-ML
Stacking or Stacked Generalization is an ensemble machine learning algorithm.</br >

It uses a meta-learning algorithm to learn how to best combine the predictions from two or more base machine learning algorithms.</br >

The benefit of stacking is that it can harness the capabilities of a range of well-performing models on a classification or regression task and make predictions that have better performance than any single model in the ensemble.</br >

Unlike bagging, in stacking, the models are typically different (e.g. not all decision trees) and fit on the same dataset (e.g. instead of samples of the training dataset).</br >
Unlike boosting, in stacking, a single model is used to learn how to best combine the predictions from the contributing models (e.g. instead of a sequence of models that correct the predictions of prior models).</br >

The architecture of a stacking model involves two or more base models, often referred to as level-0 models, and a meta-model that combines the predictions of the base models, referred to as a level-1 model. </br >
![image](https://user-images.githubusercontent.com/67821036/138847657-2db19438-c31a-4d7f-b91a-69eb037e1d74.png)


for more reference: https://medium.com/ml-research-lab/stacking-ensemble-meta-algorithms-for-improve-predictions-f4b4cf3b9237
