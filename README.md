# DeepLearning-Pytorch
Intro to Deep Learning on Pytorch by Facebook, developing neural networks for accurate results &amp; precision improvements.

## About PyTorch

At a granular level, PyTorch is a library that consists of the following components:

| Component | Description |
| ---- | --- |
| [**torch**](https://pytorch.org/docs/stable/torch.html) | a Tensor library like NumPy, with strong GPU support |
| [**torch.autograd**](https://pytorch.org/docs/stable/autograd.html) | a tape-based automatic differentiation library that supports all differentiable Tensor operations in torch |
| [**torch.jit**](https://pytorch.org/docs/stable/jit.html) | a compilation stack (TorchScript) to create serializable and optimizable models from PyTorch code  |
| [**torch.nn**](https://pytorch.org/docs/stable/nn.html) | a neural networks library deeply integrated with autograd designed for maximum flexibility |
| [**torch.multiprocessing**](https://pytorch.org/docs/stable/multiprocessing.html) | Python multiprocessing, but with magical memory sharing of torch Tensors across processes. Useful for data loading and Hogwild training |
| [**torch.utils**](https://pytorch.org/docs/stable/data.html) | DataLoader and other utility functions for convenience |

Usually one uses PyTorch either as:

- a replacement for NumPy to use the power of GPUs.
- a deep learning research platform that provides maximum flexibility and speed.

## Projects
* [MNIST DIgits Classification](https://github.com/geekykant/DeepLearning-Pytorch/tree/master/MNIST%20DIgits%20Classification)
* [Fashion MNIST Classification](https://github.com/geekykant/DeepLearning-Pytorch/tree/master/Fashion%20MNIST%20Classification)
* [CIFAR10 Image Classification](https://github.com/geekykant/DeepLearning-Pytorch/tree/master/CIFAR10%20Image%20Classification)
