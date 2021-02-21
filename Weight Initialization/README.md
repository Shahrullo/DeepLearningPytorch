# Weight Initialization

Weight initialization happens once, when a model is created and before it trains. Having good initial weights can place the neural network close to the optimal solution. This allows the neural network to come to the best solution quicker.

<img src="https://github.com/Shahrullo/DeepLearningPytorch/blob/main/Weight%20Initialization/notebook_ims/neuron_weights.png">


## Initial Weights and Observing Training Loss

We will see how different weights perform different results on the same dataset and neural network model. The following is the example of how the training loss decreases over time with diverse initial weights

<img src="https://github.com/Shahrullo/DeepLearningPytorch/blob/main/Weight%20Initialization/notebook_ims/loss_comparison_ex.png">


## Dataset and Model

We'll train an MLP to classify images from the [Fashion-MNIST database](https://github.com/zalandoresearch/fashion-mnist) to demonstrate the effect of different initial weights. As a reminder, the FashionMNIST dataset contains images of clothing types; classes = ['T-shirt/top', 'Trouser', 'Pullover', 'Dress', 'Coat', 'Sandal', 'Shirt', 'Sneaker', 'Bag', 'Ankle boot']. The images are normalized so that their pixel values are in a range [0.0 - 1.0).
