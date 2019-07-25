# MNIST Fashion Classification

This project uses Fashion MNIST dataset (https://www.kaggle.com/zalando-research/fashionmnist) to classify fashion class items in ['T-shirt/top',
                            'Trouser',
                            'Pullover',
                            'Dress',
                            'Coat',
                            'Sandal',
                            'Shirt',
                            'Sneaker',
                            'Bag',
                            'Ankle Boot'] using PyTorch DeepLearning model.

## Model
```python
class Classifier(nn.Module):
  def __init__(self):
    super().__init__()
    self.fc1 = nn.Linear(784, 256)
    self.fc2 = nn.Linear(256, 128)
    self.fc3 = nn.Linear(128, 64)
    self.fc4 = nn.Linear(64, 10)
    
  def forward(self, x):
    #Flatten the tensor
    x= x.view(x.shape[0],-1)
    
    x = F.relu(self.fc1(x))
    x = F.relu(self.fc2(x))
    x = F.relu(self.fc3(x))
    x = F.log_softmax(self.fc4(x), dim=1)
    
    return x
```

## Output
![MNIST Fashion Dataset Classification Colab Working](https://github.com/geekykant/DeepLearning-Pytorch/blob/master/Fashion%20MNIST%20Classification/output/output.png?raw=true)
