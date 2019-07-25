# MNIST Digits Classification

This project uses MNIST dataset (http://yann.lecun.com/exdb/mnist/) to classify digits using PyTorch DeepLearning model.

## Model
```python
model = nn.Sequential(nn.Linear(784,128),
                      nn.ReLU(),
                      nn.Linear(128,64),
                      nn.ReLU(),
                      nn.Linear(64,10),
                      nn.LogSoftmax(dim=1))
```

## Output
![MNIST Classification Colab Working](https://github.com/geekykant/DeepLearning-Pytorch/blob/master/CIFAR10%20Image%20Classification/output/output.png?raw=true)
