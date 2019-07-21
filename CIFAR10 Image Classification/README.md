# CIFAR10 Image Classification

This project uses CIFAR10 Image dataset (https://www.cs.toronto.edu/~kriz/cifar.html) to classify items using PyTorch DeepLearning model.

## Model
```python
#building model
model = nn.Sequential(nn.Linear(3072,60),
                      nn.ReLU(),
                      nn.Linear(60,10),
                      nn.LogSoftmax(dim=1))
```

## Output
![CIFAR10 Image Dataset Classification Colab Working](https://github.com/geekykant/DeepLearning-Pytorch/blob/master/CIFAR10%20Image%20Classification/output/output.png?raw=true)
