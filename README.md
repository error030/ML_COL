# MULTI-LEVEL COLLABORATIVE TRAINING FOR LONG-TAILED CLASSIFICATION
Python code for paper entitled "MULTI-LEVEL COLLABORATIVE TRAINING FOR LONG-TAILED CLASSIFICATION"

#### Description:
In our paper, we extend a method to balance the conflit between contrast representation task and classification task, making model easily benit from multi-task training. thanks to the proposed multi-task framework, multi-level traning strategy can be used to enhenced model performence.

#### Requirements:
*    Python 3.10.12
*    Pytorch 2.0.0+cpu
*    tqdm
*    tensorboard_logger-0.1.0
*    matplotlib


#### Long-tailed recognition accuracy:
Dataset | Backbone | Epochs | Top-1 Acc(%)
---- | :----: | :----: | :----: 
CIFAR-100-LT (beta = 100) | ResNet-32 | 200 | 47.5
CIFAR-100-LT (beta = 50) | ResNet-32 | 200 | 51.9
CIFAR-10-LT (beta = 100) | ResNet-32 | 200 | 83.3
CIFAR-10-LT (beta = 50) | ResNet-32 | 200 | 85.5
