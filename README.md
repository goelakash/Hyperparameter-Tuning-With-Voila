## (In progress) Experiment with hyperparameter tuning

This is a project to demonstrate how tuning different hyperparameters of a neural-network lead to change in accuracies. This uses the widgets library of IPython for Jupyter notebooks, and uses Voila to synthesize it into a static web-site, free of code.

The neural-net example here takes the vectorized MNIST dataset as input and passes it through 3 hidden layers to predict the input image class (i.e., value from 0-9) using a cross-entropy loss function.

Using Voíla, we synthesize the notebook into a static web-page with active widgets, and thus get a web-page where we can play around with the inputs and get the desired output.

### Frameworks:
[Pytorch](https://github.com/pytorch/pytorch)
[Voila]

### Dataset:
MNIST ([Torchvision](https://pytorch.org/docs/stable/_modules/torchvision/datasets/mnist.html))

### Demo:
Here's what the dashboard finally looks like:
![alt text](https://github.com/goelakash/Hyperparameter-Tuning-With-Voila/blob/master/images/dashboard.png)