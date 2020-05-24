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
Result Visualizations
The following image gives an idea of which model seems to achieve the best Validation Accuracy.
Validation Accuracy
![image](https://user-images.githubusercontent.com/36323558/82764314-66945180-9e2b-11ea-835e-3a66447cb9d9.png)
Validation Loss
![image](https://user-images.githubusercontent.com/36323558/82764322-74e26d80-9e2b-11ea-9926-1e84c32862f2.png)
25 misclassified images for L2 : Best Model
![image](https://user-images.githubusercontent.com/36323558/82764329-7d3aa880-9e2b-11ea-8a77-3da888255e10.png)






