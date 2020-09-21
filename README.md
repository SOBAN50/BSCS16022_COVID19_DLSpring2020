# BSCS16022_COVID19_DLSpring2020

This readme contains 2 portions:
1.COVID Detection through XRAY images
2.COVID Detection through XRAY images using focal loss.

This repository contains code and results for COVID-19 classification assignment by Deep Learning Spring 2020 course offered at Information Technology University, Lahore, Pakistan. This assignment is only for learning purposes and is not intended to be used for clinical purposes

VGG-16:

Accuracy of the network on the 1506 test images: 97 %

Accuracy of the network on the 1500 validation images: 89 %

Confusion Matrix for Test Set:
[597  23
 18   868]
 
Learning Rate = 0.001
Number of Layers added = 3
Linear()
Relu()
Dropout()
Output()
Batch Size = 16
No of threads used = 4
Momentum = 0.9
Loss = Cross Entropy and Foacal Loss
Optimizer = SGD
Epochs = 10

                                -------------------------------------------------

RESNET : 

Accuracy of the network on the 1506 test images: 96 % 

Accuracy of the network on the 1500 validation images: 88 %

Confusion Matrix for Test Set:
[587  26
 28   865]

Learning Rate = 0.001
Number of Layers added = 3
Linear()
Relu()
Dropout()
Output()
Batch Size = 16
No of threads used = 4
Momentum = 0.9
Loss = Cross Entropy
Optimizer = SGD
Epochs = 10

---------------------------------------------------------------------------------------------------------------------

DATASET : https://drive.google.com/drive/u/1/folders/1rNAaDEfQbcGlumr_3Fewia4SObTrCHAk

WEIGHTS : https://drive.google.com/drive/u/1/folders/1YdsZGesIFWBIRM6P_TZ5TvLB6ie66nyN
