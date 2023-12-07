# MULTI-LEVEL COLLABORATIVE TRAINING FOR LONG-TAILED CLASSIFICATION
Python code for paper entitled "MULTI-LEVEL COLLABORATIVE TRAINING FOR LONG-TAILED CLASSIFICATION"


#### Requirements:
*    Python 3.10.12
*    Pytorch 2.0.0+cpu
*    tqdm
*    tensorboard_logger-0.1.0
*    matplotlib


#### Long-tailed recognition accuracy:
Dataset | Backbone | Epochs | Top-1 Acc(%)
---- | :----: | :----: | :----: 
CIFAR-100-LT (imb. 100) | ResNet-32 | 200 | 47.5
CIFAR-100-LT (imb. 50) | ResNet-32 | 200 | 51.9
CIFAR-10-LT (imb. 100) | ResNet-32 | 200 | 83.3
CIFAR-10-LT (imb. 50) | ResNet-32 | 200 | 85.5
