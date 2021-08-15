# Credit Risk Analysis

## Oveview 

We were hired to help out our suit and tie banker friends on assigning risk to approve a loan or not. We were tasked with using supervised machine learning to find a model that would predict the status of future loans. After the model was built, we tested the accuracy of the model. During the test, we ran 6 different machine learnings and the best machine learning results were Easy Ensemble AdaBoost Classifier. Below is the list of the test. Besides accuracy, we wanted to find a model that had a high level of precision for low risk and a high level of precision for high risk.

1. Random Oversampling
2. SMOTE Oversampling 
3. Undersampling
4. Over & Under
5. Balanced Random Forest Classifier 
6. Easy Ensemble Classifier 

## Results 

Below are the results of the following six tests. 

## Random Oversampling 

1. Accuracy - 66.67%
2. High Risk precision - 1 %
3. Low Risk precision - 100 %

![Random Over Sampling](https://github.com/mccoycory/Credit-Risk-Analysis/blob/main/Results%20Random%20Oversampling.png)

## Undersampling

1. Accuracy - 54.47 %
2. High Risk precision - 1 %
3. Low Risk precision - 100 %

![Undersampling](https://github.com/mccoycory/Credit-Risk-Analysis/blob/main/Resutls%20Undersampling.png)

## Over & Under

1. Accuracy - 64.75 %
2. High Risk precision - 1 %
3. Low Risk precision - 100 %

![OverUnder](https://github.com/mccoycory/Credit-Risk-Analysis/blob/main/Results%20over%20%26%20under.png)

## SMOTE Oversampling

1. Accuracy - 66.23 %
2. High Risk precision - 1 %
3. Low Risk precision - 100 %

![SMOTE](https://github.com/mccoycory/Credit-Risk-Analysis/blob/main/Results%20SMOTE%20Oversampling.png)


## Balanced Random Forest Classifier 

1. Accuracy - 79.45 %
2. High Risk precision - 4 %
3. Low Risk precision - 100 %

![Balanced Random Classifier](https://github.com/mccoycory/Credit-Risk-Analysis/blob/main/Balanced%20Random%20Forest%20Classifier.png)

## Easy Ensemble Classifier 

1. Accuracy - 93.16 %
2. High Risk precision - 9 %
3. Low Risk precision - 100 %

![Easy Ensemble](https://github.com/mccoycory/Credit-Risk-Analysis/blob/main/Easy%20Ensemble%20AdaBoost%20Classifier.png)

# Summary 

Based on the 6 models that were run. We were looking for a model with high accuracy and one with a high percentage of low risk and high risk results. All of these models showed a high precentage of predicting low risk creditors. However, for a bank, they want to make sure the high risk loans are identified. The only model with a high accuracy and the highest percentage of percision is the Easy Enemble Classifier model. I would start at this model and continue to refine it until the bank can trust it to make the risk management calls. 







