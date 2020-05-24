# EVA4_Assignment8
CIFAR 10 : Classification using ResNet18
Index

Objective

Model Summary

Result Summary

Result Visualizations (misclassification/accuracy/loss)

Objective
Code uses GPU - Done

Use the RESNET18 architecture - Done

Achieve 85% accuracy, with no limit on no of parameters - Done

All the code is split and individual modules are called upon for execution - Done

Model Summary
![image](https://user-images.githubusercontent.com/36323558/82764166-76f7fc80-9e2a-11ea-8fea-4bbc1bd670f8.png)
Result Summary
Model	Train Accuracy	Test Accuracy	Epochs	Comments
ResNet18 - Normal	98.98	88.42	20	Although objective is achieved, it seems to be overfit
ResNet18 - L1	82.61	81.08	20	Objective is not achieved, but seems like a good model, more epochs could meet the criterion
ResNet18 - L2	98.85	88.70	20	Although objective is achieved, it seems to be overfit
ResNet18 - ElastiNet	82.60	81.31	20	Objective is not achieved, but seems like a good model, more epochs could meet the criterion





